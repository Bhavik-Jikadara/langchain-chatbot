# LangChain Chatbot: Interacting with Websites

Welcome to the GitHub repository for the LangChain Chatbot with Streamlit GUI! This project guides you through building a chatbot that interacts with websites, extracts information, and communicates effectively. It utilizes LangChain integrated with a Streamlit GUI for an enhanced user experience.

## Features

- **Website Interaction**: Uses LangChain to interact with and extract information from various websites.
- **Large Language Model Integration**: Compatible with GPT-4, Mistral, Llama2, and ollama. The code uses GPT-4 by default.
- **Streamlit GUI**: Provides a clean and intuitive interface built with Streamlit.
- **Python-based**: Entirely coded in Python.

## Brief explanation of how RAG works

A Retrieval-Augmented Generation (RAG) bot augments the knowledge of an LLM with additional information provided in the prompt. The process involves vectorizing the text for augmented knowledge, finding the most similar text to the prompt, and passing this text to the LLM as a prefix.

![RAG Diagram](docs/HTML-rag-diagram.jpg)

## Installation

Ensure Python is installed on your system.

- Clone the repository:

```bash
    git clone https://github.com/Bhavik-Jikadara/langchain-chatbot.git
    cd langchain-chatbot
```

- Rename the file of `.env.example` to `.env`

```bash
    cp .env.example .env
    # Add Openai API key to the .env file
    OPENAI_API_KEY="your-openai-api-key"
```

- Install the required packages:

```bash
    pip install -r requirements.txt
```

## Usage

To run the Streamlit app, use the following command:

```bash
    streamlit run src/app.py
```

## License

This project is licensed under the [Apache License 2.0](https://github.com/Bhavik-Jikadara/langchain-chatbot/blob/main/LICENSE). See the LICENSE file for more details.

---

**Note**: This project is intended for educational and research purposes. Please ensure compliance with the terms of use and guidelines of the APIs and services utilized.

---

I hope this repository serves as a valuable resource in your journey of exploring AI and chatbot development. For additional information and tutorials.

Happy Coding! 🚀👨‍💻🤖

---

**_Don't forget to star this repo if you find it useful!_**

---
