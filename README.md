# AI CLI Tool Template

This repository contains a template for creating AI-powered CLI tools using Python. It provides a solid foundation for building command-line applications that leverage various AI models like OpenAI, Anthropic, and local models through Ollama.

## Features

- Ready-to-use CLI structure with [Click](https://click.palletsprojects.com/)
- Support for multiple AI providers:
  - OpenAI (GPT models)
  - Anthropic (Claude models)
  - Azure OpenAI
  - Ollama (local models)
- Optional Retrieval-Augmented Generation (RAG) capabilities
- Configuration management
- Easy environment setup with Conda

## Usage

To use this template, you need [Copier](https://copier.readthedocs.io/en/stable/):

```bash
# Install copier
pip install copier

# Create a new project
copier copy gh:ktaletsk/ai-cli-template path/to/your-project
```

During the copy process, you'll be prompted to customize your project with options like:

- Project name and description
- Python package name
- Author information
- Whether to include Ollama support
- Whether to include RAG capabilities
- Python version

## Template Structure

The template is located in the `template/` directory and includes:

- Project configuration files
- CLI implementation
- AI integration code
- Optional RAG functionality
- Documentation

## License

This template is licensed under the MIT License. See the LICENSE file for details. 