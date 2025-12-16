# 🤖 Gerador de Conteúdo de Marketing com IA

Este projeto é uma ferramenta de automação de marketing desenvolvida em Python. Ela utiliza Grandes Modelos de Linguagem (LLMs) para criar posts otimizados para redes sociais, blogs e e-mails, adaptando o conteúdo conforme o público-alvo, tom de voz e estratégias de SEO.

O sistema utiliza a API da **Groq** (modelo `llama-3.3-70b-versatile`) orquestrada pelo **LangChain**, com uma interface amigável construída em **Streamlit**.

## 📸 Interface do Projeto

Abaixo você confere como funciona a geração de conteúdo:

([![Imagem do WhatsApp de 2025-12-15 à(s) 22 29 20_cbae7413](https://github.com/user-attachments/assets/f2191953-5bc5-4a46-8cbc-2c9370a5eb81)
]()
)

## 🚀 Funcionalidades

* **Multi-plataforma:** Gera conteúdo específico para Instagram, Facebook, LinkedIn, Blog e E-mail.
* **Personalização Completa:**
    * **Tom de voz:** Normal, Informativo, Inspirador, Urgente ou Informal.
    * **Público-alvo:** De jovens adultos a idosos.
    * **Tamanho:** Curto, Médio ou Longo.
* **Foco em SEO:** Campo dedicado para inserção de palavras-chave estratégicas.
* **Opcionais Inteligentes:** Inclusão automática de CTA (Chamada para Ação) e Hashtags relevantes.

## 🛠️ Tecnologias Utilizadas

* Python 3.12+
* Streamlit (Frontend)
* LangChain (Orquestração de IA)
* Groq API (Inferência rápida com Llama 3.3)
* Python-dotenv (Gerenciamento de variáveis de ambiente)

## 📦 Como rodar localmente

```bash
git clone [https://github.com/ThiagoR17/llm-gerador-de-conteudo.git](https://github.com/ThiagoR17/llm-gerador-de-conteudo.git)
cd llm-gerador-de-conteudo

2. Instale as dependências:

Certifique-se de ter um arquivo requirements.txt na raiz do projeto com o seguinte conteúdo:
Plaintext
streamlit
langchain-groq
langchain-core
python-dotenv
Em seguida, execute o comando para instalar:

Bash
pip install -r requirements.txt

3. Configure sua chave de API:
Crie um arquivo chamado .env na raiz do projeto e adicione sua chave da Groq (não compartilhe essa chave publicamente):

Snippet de código

GROQ_API_KEY=sua_chave_aqui
4. Execute o app:

Bash

streamlit run app.py
