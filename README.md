# Assistente de Voz com IA (OpenAI Whisper & ChatGPT)

Este projeto é um pipeline completo de áudio que atua como um assistente de voz interativo. Ele captura o áudio do usuário, transcreve para texto, processa a intenção através de um LLM e retorna a resposta sintetizada em voz.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
* **Python**: Linguagem base do pipeline.
* **OpenAI API (Whisper)**: Modelagem de Speech-to-Text (STT) para transcrição de áudio.
* **OpenAI API (GPT-3.5-Turbo)**: Processamento de Linguagem Natural para geração da resposta.
* **gTTS (Google Text-to-Speech)**: Sintetização da resposta em áudio.
* **JavaScript / HTML**: Integração com a API `MediaRecorder` do navegador para captura de áudio em ambientes de nuvem (Google Colab).

## 🚀 Como executar
1. Clone este repositório.
2. Instale as dependências: `pip install openai gtts`
3. Configure a sua variável de ambiente com a chave da API da OpenAI.
4. Execute o script em um ambiente Google Colab ou adapte para execução local.

---
*Projeto desenvolvido para fins de estudo em integração de APIs e pipelines de processamento de dados.*