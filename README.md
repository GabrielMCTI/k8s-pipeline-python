# 🚀 Pipeline com Kubernetes e GCP

Projeto de deploy automatizado utilizando Docker e Kubernetes.

## 🧠 Tecnologias

- Python (Flask)
- Docker
- Kubernetes
- GitHub Actions

## ⚙️ Pipeline

O pipeline realiza:
- Build da imagem Docker
- Push para o Container Registry
- Deploy automático no Kubernetes

## ☸️ Deploy

```bash
kubectl apply -f k8s/
