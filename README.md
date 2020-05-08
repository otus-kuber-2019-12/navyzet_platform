## navyzet_platform
navyzet Platform repository

# kubernetes-security

# Сделана домашняя работа по теме "Безопасность и управление доступом"

# Домашняя работа по теме "Сетевая подсистема Kubernetes"
- Добавлены readinessProbe и livenessProbe провероки в Pod kubernetes-intro/web-pod.yaml
- Создан Deployment kubernetes-networks/web-deploy.yaml
- Добавлены сервис kubernetes-networks/web-svc-cip.yaml
- Включён IPVS
- Установлен MetalLB
- Добавлен LoadBalancer для приложения
- Добавлены LoadBalancer для DNS
- Настроен Ingress

# Домашняя работа по теме "Хранение данных в Kubernetes"
- Добавлен Deployment приложения MinIO kubernetes-volumes/minio-headless-service.yaml
- Добавлен сервис для приложения MinIO kubernetes-volumes/minio-headless-service.yaml
- Переменные окружения с приватными данными помещены в secret
