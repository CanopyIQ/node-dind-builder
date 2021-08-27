# node-dind-builder
CircleCI v2 Node Builder

Docker no longer supports automated builds

```
# Login to docker
docker login
docker build -t canopyiq/node-dind-builder:$TAG .
docker push canopyiq/node-dind-builder:$TAG
```
