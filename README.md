# Overview
This is a very simple, bare-bones NodeJS and ExpressJS project created for you to use with Docker.

* NB: [Link to the original Udacity repo](https://github.com/udacity/nd9990-c3-microservices-exercises/tree/master/lesson-5-kubernetes-for-production/exercises/simple-express)

# Local Setup
* Install dependencies: `npm install`
* Run server: `node server.js`

# Usage
By default, the application should be loaded on `localhost:8080`. It should provide an HTTP 200 response when loaded at `localhost:8080/health`.

# Container Setup
* Build image: `docker build .`
* Run container with image: `docker run {image_id}` where `image_id` can be retrieved by running `docker images` and found under the column `IMAGE ID`

# Container teardown
* Remove container: `docker kill {container_id}` where `container_id` can be retrieved by running `docker ps` and found under the column `CONTAINER ID`
