docker build -t nginx .
docker run --name nginx -d -p 127.0.0.1:80:80 nginx
