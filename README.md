# Alias for docker


## Installation
- Using zsh:
  - Move *docker.zsh* to $HOME folder
  - Add to .zshrc:
    ```
    source ~/.docker.zsh
    ```


## How to use it
- Reset terminal
- Write dalias to see all alias:
```
➜  dalias
c => docker-compose
cb => docker-compose build
cex => docker-compose exec
cl => docker-compose logs -f --tail=100
cps => docker-compose ps
cr => docker-compose run --service-ports --rm
crci => docker-compose run --rm ci
crd => docker-compose run --service-ports --rm develop
crl => docker-compose run --service-ports --rm local
crp => docker-compose run --rm provision
crt => docker-compose run --rm test
crwt => docker-compose run --rm watchtest
cup => docker-compose up -d
cupb => docker-compose up -d --build
dex => docker exec -i -t
di => docker images
dip => docker inspect --format {{ .NetworkSettings.IPAddress }}
dkd => docker run -d -P
dki => docker run -i -t -P
dl => docker ps -l -q
dockerserver => ssh -l root 164.132.31.145
dpa => docker ps -a
dps => docker ps
drmf => docker stop $(docker ps -a -q) && docker rm $(docker ps -a -q)

```