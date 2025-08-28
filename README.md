# Mon IP

docker build -t monip:latest .

docker run -d --name mon-ip --restart unless-stopped -p 80:8091 monip:latest