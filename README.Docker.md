fro dev  :   docker compose up --build
Production :
docker build -t devops-frontend .
docker run -p 3000:80 devops-frontend

