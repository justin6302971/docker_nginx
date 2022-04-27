# nginx server Initialization Process

## Prerequisites
 * Docker
 * nginx



## Steps
1. use container service to manage reverse proxy server(create, host and destroy)
2. write compose file to setup reverse proxy server (docker-compose.yml)
3. execute docker and docker-compose command
4. connect to container use command line 
5. check .env file to setup environment variables

## Scripts

``` bash
# access postgreSql database host in docker via terminal
docker exec -it nginx_dev_local sh

```

## References
1. [nginx basic concepts](https://medium.com/starbugs/web-server-nginx-2-bc41c6268646)
2. [nginx container setting sample](https://ithelp.ithome.com.tw/articles/10244961)
3. 
