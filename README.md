# 2kolokwium

## Zadanie 1
docker run -d --name apache -p 8090:80 httpd
docker ps
docker logs apache
docker stop apache
docker rm apache
docker rmi httpd

Zadanie 2
docker build -t flask-app .
docker run -d -p 5000:5000 --name flask-container flask-app

Zadanie 3
docker compose up -d