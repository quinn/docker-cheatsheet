# Docker Cheatsheet
Random docker commands. Sometimes I don't want to go to the trouble of creating a docker-compose file. 

### Run node from docker
```sh
docker run -it --rm --entrypoint npm -v $(pwd):/home/node/app -w /home/node/app node:10.15.1 install
docker run -it --rm --entrypoint npm -v $(pwd):/home/node/app -w /home/node/app node:10.15.1 test
```
