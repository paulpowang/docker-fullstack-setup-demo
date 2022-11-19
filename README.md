# docker-fullstack-setup-demo
docker js setup



##### docker commands
$ docker build {repo name} . => repo name can be anything, "." is needed after repo name <br>
$ docker images => display existing images $ docker ps => display running images <br>
$ docker rmi {image id} => delete image $ docker kill {image id} => kill image when delete image doesn't work <br>
$ docker stop {container id} => stop running image $ docker run -p port:port {docker repo} => run the repo<br>


fullstack <br>
1. $ docker-compose build <br>
2. $ docker-compose up // will start all 3 services together app, mongo, client and that will cause issue if mongo not start first <br>
$ docker-compose up -d mongo // so do this to start mongo first $ docker-compose up -d app // then app <br>
$ docker-compose up -d client // then client <br>
$ docker-compose stop // stop all 3 containers<br>
