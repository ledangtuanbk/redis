set enviroment variable
```
export REDIS_HOME=/srv/redis
```
and add previous line to .bashrc file

# Redis
docker run -dit -p 6379:6379 --restart=always -v $REDIS_HOME/data:/data --name redis ledangtuanbk/redis:5.0
