# Dockerfile for Frontend Service
FROM python:3.12-slim
 # Frontend Dockerfile
 WORKDIR /app
 
 COPY requirements.txt ./
 RUN pip install --no-cache-dir -r requirements.txt
 
 COPY src/ ./src/
 COPY main.py ./main.py
 
 EXPOSE 5002
 
 CMD ["python", "main.py"]




RUN pip install --no-cache-dir -r requirements.txt



CMD ["python", "main.py"]

