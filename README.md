# CodeGenius AI Assistant 🤖💻

**CodeGenius** is an AI-powered code generation assistant designed to help developers generate production-ready code across multiple programming languages (Python, JavaScript, Java, C#, Go). It also generates documentation 📚 and tests 🧪 for the generated code.

## Features ✨

- **Multi-Language Support**: Supports Python 🐍, JavaScript 🌐, Java ☕, C# 💻, and Go 🚀 for code generation.
- **Project Context Awareness**: Understands the project's files and imports to generate code that aligns with the existing codebase.
- **Documentation Generation**: Automatically generates language-specific documentation (e.g., Google-style docstrings for Python, JSDoc for JavaScript).
- **Test Generation**: Generates unit tests, integration tests, and performance tests.
- **Security & Best Practices**: Generates code following security best practices 🔒 and the respective language standards 📏.
- **Interactive Web Interface**: Use the assistant directly via a Gradio web interface 🌍.

## Requirements ⚙️

To use **CodeGenius AI Assistant**, you need:

- Python 3.x 🐍
- Required Python libraries (install with `pip`):
  - `gradio`: For building the interactive web UI.
  - `google-generativeai`: For interfacing with Google's Gemini 2.0 Flash model for code generation.

To install the necessary libraries, run:

```bash
pip install gradio google-generativeai
