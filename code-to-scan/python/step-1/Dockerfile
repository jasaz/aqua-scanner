FROM docker.io/library/python:3.13-bookworm

WORKDIR /app
COPY *.py .
COPY requirements.txt .

RUN python3 -m pip install -r requirements.txt
ENTRYPOINT ["python", "flask-demo.py"]
