# jupyter-js-docker

To build the docker image

`docker-compose build -t franz/jupyter-js .`

To start the docker image

`docker container run -p 8888:8888 -v $(pwd):/usr/notebooks franz/jupyter-js`

Do NOT run in daemon mode, you will need the console output to get the link with the token for jupyter to login