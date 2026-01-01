FROM python:3.11-slim

RUN useradd -m appuser
USER appuser

WORKDIR /app
COPY . .

CMD ["python", "app.py"]
