# Deep_Learning.AI_Agentic_AI

Repo with materials for the DeepLearning.AI Agentic AI Course

## Project Setup

This project uses [uv](https://github.com/astral-sh/uv) as the Python package manager, which provides fast and reliable dependency management.

### Prerequisites

- Python 3.12 or higher
- uv package manager

### Installation

1. Install uv (if not already installed):
```bash
pip install uv
```

2. Install project dependencies:
```bash
uv sync
```

This will create a virtual environment and install all required packages including Jupyter.

### Running Jupyter Notebooks

To start Jupyter and work with the notebooks:

```bash
uv run jupyter notebook
```

Or to use JupyterLab:

```bash
uv run jupyter lab
```

The notebooks are located in the `notebooks/` directory.

### Project Structure

```
.
├── notebooks/           # Jupyter notebooks for agentic AI practice
│   └── agentic_ai_practice.ipynb
├── pyproject.toml      # Project configuration and dependencies
├── .python-version     # Python version specification
└── README.md           # This file
```

### Adding Dependencies

To add new packages to the project:

```bash
uv add <package-name>
```

For example, to add common AI/ML libraries:

```bash
uv add openai anthropic langchain
```

### Development

The project includes a sample notebook (`notebooks/agentic_ai_practice.ipynb`) to get started with agentic AI concepts.
