# 🎙️ Assistente de Voz Inteligente: Whisper + GPT + gTTS

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![OpenAI](https://img.shields.io/badge/API-OpenAI-orange.svg)](https://openai.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📋 Sobre o Projeto

Este projeto foi desenvolvido como desafio final do Bootcamp na **DIO (Digital Innovation One)**. O objetivo é criar um fluxo completo de conversação por voz utilizando Inteligência Artificial, replicando a funcionalidade de assistentes como Alexa ou Siri.

O sistema é capaz de ouvir o usuário, entender o contexto da pergunta, gerar uma resposta inteligente e "falar" essa resposta de volta.

## 🛠️ Tecnologias e Ferramentas

* **OpenAI Whisper**
* **OpenAI GPT-3.5 Turbo**
* **gTTS (Google Text-to-Speech)**
* **Google Colab**

## ⚙️ Arquitetura do Sistema

1.  **Entrada**: Captura de áudio do microfone através de um script JavaScript integrado ao Python.
2.  **Transcrição**: O áudio é enviado ao modelo Whisper, que o converte em texto.
3.  **Processamento**: O texto transcrito é enviado à API do ChatGPT, que gera uma resposta relevante.
4.  **Saída**: A resposta é convertida em um arquivo `.mp3` pelo gTTS e reproduzida automaticamente.

## ⚠️ Observações de Desenvolvimento (Status da API)

O código foi totalmente testado e validado. No entanto, devido ao uso de contas de teste com créditos limitados na OpenAI, o sistema pode retornar erro. 

Link : https://colab.research.google.com/drive/1m8tBcPfN8rvGz-MTVvrRwx2pGinX1coz?usp=sharing
