# 🖼️ Agente de Análise de Imagens com IA

![Python](https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-AI_Foundry-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-SDK-412991?style=for-the-badge&logo=openai&logoColor=white)
![Vision AI](https://img.shields.io/badge/Multimodal-Vision_AI-8A2BE2?style=for-the-badge)
![JSON](https://img.shields.io/badge/JSON-Structured_Output-000000?style=for-the-badge&logo=json&logoColor=white)
![Pillow](https://img.shields.io/badge/Pillow-Image_Processing-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 📌 Sobre o projeto

Este projeto é um **Agente de Inteligência Artificial para Análise de Imagens**, desenvolvido utilizando **Python, Streamlit e Microsoft Azure AI Foundry**.

O sistema permite que o usuário envie uma imagem pela interface web. A imagem é processada e enviada para um **modelo multimodal com capacidade de visão**, responsável por realizar uma análise visual estruturada.

O resultado é retornado em formato JSON e apresentado de maneira organizada na interface do Streamlit.

---

## 🤖 Funcionalidades

O agente é capaz de analisar:

- 🖼️ Conteúdo geral da imagem
- 👤 Presença de pessoas reais
- 🔢 Quantidade aproximada de pessoas
- 🎨 Cores predominantes
- 🔍 Objetos e elementos presentes
- ✨ Qualidade geral da imagem
- 🔎 Nitidez
- 💡 Iluminação
- 🌓 Contraste
- 📊 Nível de confiança da análise
- 🏷️ Palavras-chave relacionadas à imagem

O agente também diferencia **pessoas reais** de personagens fictícios, como personagens de anime, desenhos, ilustrações, avatares, bonecos e personagens 3D.

---

## 🧠 Microsoft Azure AI Foundry

O projeto utiliza um modelo multimodal implantado no **Microsoft Azure AI Foundry**.

A integração utiliza:

- Microsoft Azure AI Foundry
- Modelo multimodal com visão
- OpenAI Python SDK
- Responses API
- Entrada de imagem em Base64
- Structured Outputs
- JSON Schema
- Prompt Engineering

---

## 🛠️ Tecnologias utilizadas

| Tecnologia | Utilização |
|---|---|
| Python | Linguagem principal |
| Streamlit | Interface web |
| Microsoft Azure AI Foundry | Hospedagem e execução do modelo de IA |
| OpenAI SDK | Comunicação com o endpoint do modelo |
| Responses API | Envio de texto + imagem |
| Pillow | Manipulação e leitura das imagens |
| Base64 | Conversão da imagem para envio à API |
| Python Dotenv | Gerenciamento das variáveis de ambiente |
| JSON Schema | Estruturação e validação da resposta |
| GitHub | Versionamento do projeto |

---

## 📁 Estrutura do projeto

```text
Agente-de-Analise-de-Imagens/
│
├── app.py
├── image_agent.py
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
