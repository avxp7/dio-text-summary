
# Resumidor de Textos Inteligente com Voz 🤖🎙️

Repositório dedicado ao projeto prático de Inteligência Artificial desenvolvido durante o curso, focado em facilitar a leitura e compreensão de grandes volumes de texto através de IA Generativa e comandos de voz.

## 📌 O que é

Este projeto consiste em uma aplicação em **Python** que utiliza a **API do Google Gemini** para processar e resumir textos extensos. O diferencial está na interface de interação: o usuário insere o conteúdo e utiliza comandos de voz para acionar a inteligência, recebendo o resultado tanto em texto quanto em áudio.

O curso abordou os pilares fundamentais da IA, desde algoritmos de Machine Learning e Deep Learning até Visão Computacional e as modernas IAs Generativas (LLMs e SLMs).

## 🚀 O Projeto

A aplicação funciona como um assistente de produtividade. O fluxo de funcionamento é:

1. **Entrada de Dados:** O usuário insere o texto longo no sistema.
2. **Interação por Voz:** O sistema aguarda o comando de voz ("ENVIAR" ou "RESUMIR").
3. **Processamento (LLM):** Através da biblioteca do Google Generative AI, o comando é enviado ao modelo Gemini, que gera um resumo conciso.
4. **Saída de Áudio (TTS):** O resumo gerado é convertido em fala utilizando a biblioteca **gTTS** (Google Text-to-Speech).

---

## 🛠️ Tecnologias e Bibliotecas

* **Linguagem:** Python
* **Ambiente:** Jupyter Notebook
* **IA Generativa:** Google Gemini API (`google-generativeai`)
* **Conversão de Voz:** `gTTS`
* **Processamento de Linguagem Natural:** Conceitos de PLN aplicados via API.

---

## 💡 Aprendizados

* **Integração de APIs:** Configuração e manipulação de requisições em tempo real com modelos de linguagem de larga escala.
* **Engenharia de Prompt:** Estruturação de instruções para garantir resumos precisos e úteis.
* **Acessibilidade (Speech-to-Text & Text-to-Speech):** Implementação de fluxos onde a IA não apenas escreve, mas interage por meio da fala.
* **Redução de Ruído:** Técnicas para filtrar o essencial em textos densos, evitando alucinações da IA durante o resumo.

---

## 🎯 Objetivo

Demonstrar a aplicação prática de modelos de IA Generativa no dia a dia, provando como a automação de tarefas simples — como a leitura de textos longos — pode ser potencializada com o uso correto de Python e ferramentas modernas de IA.

---

### Como usar este repositório:

> **Nota:** Para rodar este projeto, você precisará de uma chave de API do Google AI Studio e instalar as dependências via pip: `pip install google-generativeai gTTS`.

## 🛠️ Instalação 

Clone o repositório.
Crie seu arquivo .env com sua chave da API do Gemini.
Instale as dependências: pip install -r requirements.txt.
Nota: Caso tenha erro ao instalar o PyAudio, instale as ferramentas de áudio do seu sistema operacional (como pipwin no Windows ou portaudio no Linux).


---
