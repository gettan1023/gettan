# README

# Requirement
Docker
docker-compose

# Usage
``` bash
$ git clone git@github.com:H0R15H0/rails-react-app.git gettan
$ cd gettan
$ git clone git@github.com:H0R15H0/react-app.git frontend
$ git clone git@github.com:H0R15H0/rails-api.git api
$ echo "PORT=3010" > frontend/.env
$ docker-compose up --build
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