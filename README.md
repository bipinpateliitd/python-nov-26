# Python GenAI Tutorial

This repository contains a collection of Python tutorials focused on Generative AI, covering topics from basic Python concepts to using LLMs like Gemini, Groq, and Ollama.

## Setup Instructions using `uv`

This project uses `uv` for minimal and fast Python package management.

### 1. Install `uv` (if not already installed)

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

### 2. Create a Virtual Environment

```bash
uv venv
```

This will create a `.venv` directory in your project root.

### 3. Activate the Environment

On Linux/macOS:
```bash
source .venv/bin/activate
```

On Windows:
```bash
.venv\Scripts\activate
```

### 4. Install Dependencies

```bash
uv pip install .
```

## Environment Configuration

This project requires API keys for accessing various LLM providers. You need to store these keys in a `.env` file.

1.  Create a file named `.env` in the root directory of the project.
2.  Add your API keys to the file in the following format:

```env
GOOGLE_API_KEY=your_google_api_key_here
GROQ_API_KEY=your_groq_api_key_here
OPENAI_API_KEY=your_openai_api_key_here
# Add other keys as needed
```

**Note:** Never commit your `.env` file to version control.

## Running the Tutorials

You can run the Jupyter notebooks using VS Code or by installing Jupyter Lab:

```bash
uv pip install jupyterlab
jupyter lab
```
