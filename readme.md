# Module 8 Assignment

### How to run locally

Create a virtual environment

```
python3 -m venv venv
```

Activate virtual environment

```
source venv/bin/activate
```

Install dependencies

```
pip3 install -r requirements.txt
```

Run the application

```
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```
