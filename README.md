# SIMPLE_API

1. py -3 -m venv .venv
2. .venv\scripts\activate

3. python -m pip install --upgrade pip
4. pip install fastapi
5. pip install "uvicorn[standard]"

6. RUN: uvicorn main:app --reload

7. uvicorn main:app --host 0.0.0.0 --port 10000
