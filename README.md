## docker build
docker build -t docker-node-app .

## docker run
docker run --rm  -p 39160:8080 -d -v server.js:server.js docker-node-app

