# local-concourse
Concourse in docker!  
https://concourse-ci.org/

### Run
```bash
docker-compose up -d
```

### Command Line tool
```bash
brew install fly
fly login -t local -u test -p test -c http://127.0.0.1:8080
fly -t local sync
```

### Concourse Web UI
[http://127.0.0.1:8080](http://127.0.0.1:8080/)

Username: `test`  
Password: `test`
