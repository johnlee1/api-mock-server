FROM python:3.6-alpine

COPY requirements.txt/ app/
COPY templates/ app/templates
COPY app.py app/

WORKDIR /app

RUN pip install -r requirements.txt

EXPOSE 5000