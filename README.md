# FastAPI Tutorial
This is a simple walk through the FastAPI documentation for exercising.
## Setup
Set up virtual environment:
```bash
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
```
For Linux or MacOS run this instead:
```bash
python -m venv env
source ./env/bin/activate
pip install -r requirements.txt
```

## Running the app
`uvicorn main:app --reload`