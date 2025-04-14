# Web Summarizer with Ollama

This project provides a streamlined Python script that extracts clean text content from a webpage and summarizes it using a locally hosted Ollama model, such as `gemma3:12b`. The script supports system-level prompting to guide the style, tone, or structure of the generated summary.

## Features

- Extracts and cleans raw webpage text
- Summarizes content using a local Ollama LLM
- Supports structured system prompts (e.g., "Summarize like a journalist")
- Logs performance metrics including token usage and generation time
- Structured and readable logging to file and console

## Requirements

- Python 3.8+
- Ollama installed and running locally
- Dependencies:
  ```bash
  pip install requests beautifulsoup4
