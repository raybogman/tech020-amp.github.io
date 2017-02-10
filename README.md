# tech020-amp.github.io


## Use full commands

wget -qO- https://get.docker.com/ | sh

curl -L "https://github.com/docker/compose/releases/download/1.11.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

chmod +x /usr/local/bin/docker-compose

# Useful Docker commands

* docker ps -a
* docker images
* docker exec -it <image_id> bash
* docker stop
* docker rm -f $(docker ps -a -q)
* docker rmi -f $(docker images -q)

* docker-compose up
* docker-compose stop
* docker-compose rm
* docker-compose config
* docker-compose ps


# Useful Jekyll stuff

* jekyll build --watch --incremental

# Useful AMP stuff

* https://validator.ampproject.org
* https://chrome.google.com/webstore/detail/amp-validator/nmoffdblmcmgeicmolmhobpoocbbmknc
