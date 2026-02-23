FROM python:3.12-slim

WORKDIR /app

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY src/main.py ./main.py
COPY src/templates ./templates

EXPOSE 5002

CMD ["python", "main.py"]
