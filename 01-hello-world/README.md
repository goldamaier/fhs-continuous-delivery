# Docker Assignment
## Build
```bash
docker build -t goldamaier/01-hello-world .
```
## Run
```bash
docker run -d --name hellohannes -p 3000:3000 goldamaier/01-hello-world
```
## Stop
```bash
docker stop hellohannes
```
## Start again
```bash
docker start hellohannes
```
## Remove Container
```bash
docker rm hellohannes
```