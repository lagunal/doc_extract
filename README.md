# Document Extract

Document Extract is a Python project for extracting, structuring, and exploring information from documents. It is intended to support document parsing, validation, token-aware processing, semantic storage, and an interactive interface for working with extracted content.

## Planned packages

- `requests` — make HTTP requests to external services.
- `ipykernel` — support notebook-based exploration and development.
- `python-dotenv` — load configuration values from a `.env` file.
- `openai` — access OpenAI models for document-processing workflows.
- `pydantic` — define and validate structured extracted data.
- `docling` — parse and convert document content into usable formats.
- `lancedb` — store and query document embeddings and metadata.
- `streamlit` — build an interactive web interface.
- `tiktoken` — estimate and manage text token counts.

## Environment

Install the project's dependencies and run commands through uv:

```zsh
uv sync
uv run python your_script.py
```
