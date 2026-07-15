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

<img width="1582" height="801" alt="part1_chatapp" src="https://github.com/user-attachments/assets/abfd65ae-d18a-4319-b3df-0f52ddbb76a0" />
<img width="1487" height="752" alt="part2-responseapi" src="https://github.com/user-attachments/assets/da37d08e-ecd8-4d23-8d84-91b37a60eb98" />
<img width="1462" height="805" alt="conversation-tracking" src="https://github.com/user-attachments/assets/e7116270-a9b2-49a7-9b69-6da5fd823ba5" />
<img width="1537" height="827" alt="asynchronousApiUse" src="https://github.com/user-attachments/assets/4b08a9c7-bf25-4594-868d-96595109aa50" />




### chat-async.py

Paste your console output from running the async chat app here.

### tools-app.py

Paste your console output from running the tools app here.
