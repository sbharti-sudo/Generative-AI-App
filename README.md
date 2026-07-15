# Generative AI App

This repository contains two Python samples for Microsoft Foundry:

- `chat-app/` for a chat application using the Responses API
- `tools-app/` for a tool-enabled app using `web_search` and `file_search`

## Prerequisites

- Python 3.13
- Azure CLI
- Access to a Microsoft Foundry project
- A deployed model such as `gpt-5.2`

## Repository Layout

- `chat-app/` contains `chat-app.py`, `chat-async.py`, `requirements.txt`, and `.env.example`
- `tools-app/` contains `tools-app.py`, `requirements.txt`, `.env.example`, and the brochure PDFs used by `file_search`

## Setup

1. Create and activate a Python virtual environment in each app folder.
2. Install dependencies with `pip install -r requirements.txt`.
3. Copy `.env.example` to `.env` in each app folder.
4. Fill in `AZURE_OPENAI_ENDPOINT` and `MODEL_DEPLOYMENT` in the `.env` file.
5. Run `az login` before starting the apps.

## Run the chat app

From `chat-app/`:

```powershell
python chat-app.py
```

To run the async version:

```powershell
python chat-async.py
```

## Run the tools app

From `tools-app/`:

```powershell
python tools-app.py
```

## Sample Output

### chat-app.py

Paste your console output from running the chat app here.

### chat-async.py

Paste your console output from running the async chat app here.

### tools-app.py

Paste your console output from running the tools app here.
