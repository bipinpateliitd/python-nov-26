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

## Tutorials Included

This repository contains the following tutorials:

### Python Basics
- **`data_types.ipynb`** - Introduction to Python data types
- **`operations.ipynb`** - Basic Python operations and operators
- **`strings_genai_tutorial.ipynb`** - String operations with GenAI examples
- **`string_operations.ipynb`** - String manipulation techniques
- **`conditions.ipynb`** - Conditional statements and logic
- **`loops.ipynb`** - For loops, while loops, and loop control
- **`list.ipynb`** - Working with lists in Python
- **`list_comprehension.ipynb`** - List comprehension techniques

### Advanced Python Concepts
- **`functions.ipynb`** - Functions basics
- **`functions_comprehensive.ipynb`** - Comprehensive guide to Python functions
- **`classes_and_objects.ipynb`** - Object-oriented programming basics
- **`classes_and_objects-mod.ipynb`** - Modified/advanced OOP concepts
- **`class_practice2.ipynb`** - OOP practice exercises
- **`classes_practice.ipynb`** - Additional OOP practice
- **`tata_motors_oop_tutorial.ipynb`** - Real-world OOP example using Tata Motors case study
- **`decorators.ipynb`** - Python decorators explained
- **`iterators_and_genrators.ipynb`** - Iterators and generators

### Generative AI with LLMs
- **`llm_gemini.ipynb`** - Using Google's Gemini API
- **`llm_groq.ipynb`** - Using Groq API for fast inference
- **`llm_ollama.ipynb`** - Running local LLMs with Ollama
- **`model_routing.ipynb`** - Routing between different LLM models
- **`genai_advertisment.ipynb`** - GenAI for advertisement generation
- **`movie_advertisment.ipynb`** - Movie advertisement generation with AI

## Running the Tutorials

You can run the Jupyter notebooks using VS Code or by installing Jupyter Lab:

```bash
uv pip install jupyterlab
jupyter lab
```
