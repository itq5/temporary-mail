
docker build -t mail .
docker run --name mail -d -p 25:25 -p 3002:3002 mail
