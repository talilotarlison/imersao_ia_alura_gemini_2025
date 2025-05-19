# Imersão IA Alura Gemini 2025

Este repositório contém materiais, notebooks e exemplos práticos do projeto **Imersão IA Alura Gemini 2025**, focado em aplicações de Inteligência Artificial com a API Gemini do Google, integrando agentes de IA e experimentação interativa via Google Colab (Python Notebooks).

---

## ✨ Visão Geral

Nesta imersão você irá:

- Aprender a integrar a API Gemini do Google para geração de texto, imagens e outros recursos de IA generativa.
- Explorar conceitos de agentes de IA e fluxos de automação inteligente.
- Experimentar hands-on com notebooks Python, usando o Google Colab para rápida prototipagem.
- Desenvolver projetos práticos, desde chatbots até sistemas de recomendação, utilizando as ferramentas modernas de IA.

---

## 📚 Conteúdo

- **Introdução à API Gemini**
  - O que é a Gemini?
  - Como funciona a API Gemini do Google?
- **Configuração do Ambiente**
  - Como obter sua chave de API Gemini
  - Instalação de dependências
  - Acesso e uso do Google Colab
- **Exemplos de Uso**
  - Geração de texto com Gemini
  - Criação de agentes de IA conversacionais
  - Geração de imagens e análise multimodal
- **Projetos Práticos**
  - Chatbot com personalidade customizada
  - Sistema de perguntas e respostas
  - Análise de sentimentos e sumarização
- **Desafios de Imersão**
  - Propostas de desafios para praticar e expandir o conhecimento

---

## 🚀 Como começar

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/imersao_ia_alura_gemini_2025.git
   cd imersao_ia_alura_gemini_2025
   ```

2. **Instale as dependências**
   - Recomendado: Use um ambiente virtual (venv, conda, etc)
   - Instale os requisitos:
     ```bash
     pip install -r requirements.txt
     ```

3. **Configure sua chave API Gemini**
   - Crie um arquivo `.env` com a variável:
     ```
     GEMINI_API_KEY=sua_chave_aqui
     ```

4. **Abra os Notebooks no Google Colab**
   - Navegue até a pasta `/notebooks`
   - Clique no notebook desejado (`.ipynb`) e selecione “Abrir com Google Colab”.

---

## 🧩 Estrutura do Projeto

```
imersao_ia_alura_gemini_2025/
│
├── notebooks/              # Notebooks interativos no Google Colab
│   ├── 01_intro_gemini.ipynb
│   ├── 02_agentes_ia.ipynb
│   └── ...
│
├── src/                    # Scripts auxiliares e módulos Python
│
├── requirements.txt        # Dependências do projeto
├── .env.example            # Exemplo de configuração de variáveis de ambiente
├── README.md               # Este arquivo
└── LICENSE
```

---

## 🛠️ Tecnologias Utilizadas

- Python 3.10 ou superior
- Google Colab / Jupyter Notebooks
- API Gemini do Google
- Bibliotecas: `requests`, `google-generativeai`, `dotenv`, entre outras

---

## 📄 Como obter a API Gemini

1. Acesse [Google AI Studio](https://aistudio.google.com/app/apikey) e gere sua chave de API Gemini.
2. Copie e cole sua chave no arquivo `.env` conforme instruções deste README.

---

## 🤖 Exemplos de Código

### Consulta simples à API Gemini

```python
import google.generativeai as genai
import os
from dotenv import load_dotenv

load_dotenv()
genai.configure(api_key=os.getenv("GEMINI_API_KEY"))

response = genai.generate_text(
    model="gemini-pro",
    prompt="Explique brevemente o que é IA generativa."
)
print(response.text)
```

---

## 👩‍💻 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests com melhorias, exemplos ou dúvidas.

---

## 📢 Licença

Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

---

## 🧠 Créditos

- Projeto desenvolvido durante a Imersão IA Alura 2025.
- Inspiração, facilitação e curadoria por [Alura](https://www.alura.com.br/).
