FROM python:3.11-slim

RUN adduser --disabled-password --no-create-home appuser


RUN apt-get update && \
    apt-get install -y --no-install-recommends gcc libpq-dev && \
    apt-get clean && rm -rf /var/lib/apt/lists/*

WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

USER appuser

ENV FLASK_APP=app.py
EXPOSE 5000

CMD ["python", "app.py"]

