# reactProject-infra
# reactProject-odk-infra

This repository manages the fullstack development environment for the ODK Project using Docker Compose.

## 프로젝트 구성

- **Backend:** [`reactProject-odk-api`](https://github.com/your-id/reactProject-odk-api)
- **Frontend:** [`reactProject-odk-react-app`](https://github.com/your-id/reactProject-odk-react-app)

## 실행 방법

```bash
# Clone repositories
git clone https://github.com/your-id/reactProject-odk-infra.git
git clone https://github.com/your-id/reactProject-odk-api.git
git clone https://github.com/your-id/reactProject-odk-react-app.git

# Move into infra folder
cd reactProject-odk-infra

# Run Docker
docker-compose up --build
