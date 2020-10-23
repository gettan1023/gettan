# README

# Requirement
Docker
docker-compose

# Usage
``` bash
$ git clone git@github.com:gettan1023/gettan.git gettan
$ cd gettan
$ git clone git@github.com:gettan1023/frontend.git frontend
$ git clone git@github.com:gettan1023/api.git api
$ echo "PORT=3010" > frontend/.env
$ docker-compose up --build
$ docker-compose exec api rails db:create
```

# Open
```
rails: localhost:3010/
react: localhost:3000/
```

# Change remote repository
```
$ git remote set-url origin https://github.com/USERNAME/REPOSITORY.git
```