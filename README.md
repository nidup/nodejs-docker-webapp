# nodejs-docker-webapp

Dockerizing a Node.js web app

Playing with this tutorial https://nodejs.org/en/docs/guides/nodejs-docker-webapp/

docker build -t nidup/node-web-app .
docker run -p 49160:8080 -d nidup/node-web-app
curl -i localhost:49160