# Gen AI App Using DeepSeek-R1 with LangChain and Ollama

This repository contains a Generative AI application that utilizes the DeepSeek-R1 model with LangChain and Ollama for local inference. The app provides a chat interface built with Streamlit, enabling users to interact with the DeepSeek-R1 model efficiently.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Tools and Technologies](#tools-and-technologies)

## Introduction

The Gen AI App is designed to facilitate seamless interactions with locally hosted DeepSeek-R1 models. Users can select between different model sizes (`deepseek-r1:1.5b` and `deepseek-r1:3b`) and maintain a complete chat history using `st.session_state`. The app leverages LangChain's `ChatOllama` for integration with Ollama.

## Features

- Supports DeepSeek-R1 models (deepseek-r1:1.5b and deepseek-r1:3b).

- Runs locally using Ollama for efficient execution.

- Streamlit-based UI for easy interaction.

- Full chat history management with st.session_state.

- Customizable prompts using LangChain.

## Installation

1. Clone the repository to your local machine:

```
   git clone https://github.com/srijosh/Gen-AI-App-Using-DeepSeek-R1-with-LangChain-and-Ollama.git
```

2. Navigate to the project directory:

```
   cd Gen-AI-App-Using-DeepSeek-R1-with-LangChain-and-Ollama
```

3. Install the required dependencies:

```
   pip install -r requirements.txt
```

4. Download and run Ollama with DeepSeek-R1 locally:

```
   ollama run deepseek-r1:1.5b

```

## Usage

1. Run the Streamlit app:

```
   streamlit run app.py
```

## Tools and Technologies

- DeepSeek-R1: Open-source large language models.

- Ollama: Local model execution framework.

- LangChain: AI model orchestration and prompt management.

- Streamlit: Interactive UI for the chatbot.
