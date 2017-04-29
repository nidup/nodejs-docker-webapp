## Dockerizing a Node.js web app

Playing with this tutorial https://nodejs.org/en/docs/guides/nodejs-docker-webapp/

## Build

```
docker build -t nidup/node-web-app .
```

## Run

```
docker run -p 49160:8080 -d nidup/node-web-app
```

## Test

```
curl -i localhost:49160
```
