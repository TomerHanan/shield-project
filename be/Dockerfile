# Dockerfile for Backend Service
FROM python:3.12-slim
 # Backend Dockerfile
 WORKDIR /app
 
 COPY requirements.txt ./
 RUN pip install --no-cache-dir -r requirements.txt
 
COPY src/ ./src/
COPY src/main.py ./main.py
 
 EXPOSE 5001
 
 CMD ["python", "main.py"]




RUN pip install --no-cache-dir -r requirements.txt



CMD ["python", "main.py"]

EXPOSE 5001