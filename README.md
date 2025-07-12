# CodeLlama

CodeLlama is an interactive code assistant powered by a local language model, designed to help users with programming questions and code generation. The assistant, named **CodeGuru**, provides code explanations, examples, and solutions through a simple web interface.

## Features

- Ask coding questions and get instant answers.
- Supports code generation and explanations for various programming languages.
- Remembers conversation history for context-aware responses.
- User-friendly web interface powered by Gradio.

## Getting Started

### Prerequisites

- Python 3.8+
- [Ollama](https://ollama.com/) or a compatible local LLM server running at `http://localhost:11434`
- Required Python packages (see [requirements.txt](requirements.txt))

### Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/codellama.git
    cd codellama
    ```

2. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Ensure your LLM server is running and has the `codeguru` model available.

### Usage

```sh
python [app.py](http://_vscodecontentref_/0)
```


Open the provided URL in your browser to interact with CodeGuru.

File Structure
[app.py](http://_vscodecontentref_/1) — Main application file with Gradio interface.
modelfile — Model configuration for the LLM backend.
.gradio/flagged/ — Stores flagged user interactions.
[requirements.txt](http://_vscodecontentref_/2) — Python dependencies.
License
This project is licensed under the MIT License. See LICENSE
