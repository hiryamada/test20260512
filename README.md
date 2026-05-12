# test20260512

## Overview
This project implements a simple API that returns `Hello World` using FastAPI.

## Directory Structure
- `src/`: Source code for the API
- `tests/`: Unit tests using pytest

## Setup
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## How to Run
Start the API server with the following command:

```bash
uvicorn src.main:app --reload
```

After startup, access `http://127.0.0.1:8000/` to get the following JSON response:

```json
{"message": "Hello World"}
```

## Testing
Run unit tests with the following command:

```bash
pytest
```
