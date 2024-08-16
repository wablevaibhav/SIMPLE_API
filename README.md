# SIMPLE_API

py -3 -m venv .venv
.venv\scripts\activate

python -m pip install --upgrade pip
pip install fastapi
pip install "uvicorn[standard]"

TO RUN:
uvicorn main:app --reload
