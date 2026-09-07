# Node.js Docker Deployment

Simple Node.js app containerized with Docker and deployed via Docker Hub.

## Run locally
npm install
node app.js

## Docker
docker build -t samsmylz/nodejs-app:1.0 .
docker run -d -p 3000:3000 samsmylz/nodejs-app:1.0

## Screenshots
### Docker Build
![build](screenshots/docker-build.png)

### Docker Hub
![hub](screenshots/dockerhub-image.png)

### Running Container
![ps](screenshots/docker-ps.png)

### Live App
![live](screenshots/live-app.png)