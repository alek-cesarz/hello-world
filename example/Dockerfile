FROM python:3.10

RUN mkdir /app
WORKDIR /app
COPY requirements.txt .

COPY processor.py .
RUN pip install -r requirements.txt
