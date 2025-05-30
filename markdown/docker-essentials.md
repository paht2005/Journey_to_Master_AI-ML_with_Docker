
# 🔧 Docker Essentials for AI/ML

## 🧱 Images vs Containers
- **Image**: Blueprint with code, dependencies, base OS, etc.
- **Container**: A live, isolated instance of an image.

## 🔑 Key Docker Commands
```bash
docker build -t my-image .
docker run -p 8888:8888 my-image
docker ps
docker logs <container-id>
docker exec -it <container-id> bash
```

## 🔌 Networking, Volumes, Detached Mode
- `-p 8000:8000`: port mapping
- `-v $PWD:/app`: mount host dir
- `-d`: run in background

## 🔄 Lifecycle Management
- `stop/start`, `rm`, `rmi`, `logs`, `exec` for container/image control
