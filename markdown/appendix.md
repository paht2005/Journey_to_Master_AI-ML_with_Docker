
# 📁 Appendix

## 🧾 Docker Command Cheatsheet
```bash
docker build -t myapp .
docker run -p 8080:80 myapp
docker exec -it myapp bash
docker logs myapp
docker stop myapp
```

## 📂 Sample Dockerfile
```Dockerfile
FROM python:3.10-slim
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD ["python", "app.py"]
```

## ✅ Deployment Checklist
- [x] Build & tag Docker image
- [x] Test container locally
- [x] Push to Docker Hub
- [x] Deploy to Hugging Face / Kubernetes
