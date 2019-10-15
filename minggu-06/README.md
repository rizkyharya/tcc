# PRAKTIKUM KCC MINGGU 6

URL

https://www.katacoda.com/courses/docker/deploying-first-container

https://www.katacoda.com/courses/docker/create-nginx-static-web-server

https://www.katacoda.com/courses/docker/2

STEP 1 "UNTUK MENCARI IMAGE UNTUK REDIS"

gunakan perintah ```docker search redis```

```
$ docker search redis
NAME                             DESCRIPTION                                     STARS               OFFICIAL            AUTOMATED
redis                            Redis is an open source key-value store that…   7412                [OK]
bitnami/redis                    Bitnami Redis Docker Image                      129                                     [OK]
sameersbn/redis                                                                  77                                      [OK]
grokzen/redis-cluster            Redis cluster 3.0, 3.2, 4.0 & 5.0               61
rediscommander/redis-commander   Alpine image for redis-commander - Redis man…   31                                      [OK]
kubeguide/redis-master           redis-master with "Hello World!"                30
redislabs/redis                  Clustered in-memory database engine compatib…   23
oliver006/redis_exporter          Prometheus Exporter for Redis Metrics. Supp…   18
arm32v7/redis                    Redis is an open source key-value store that…   17
redislabs/redisearch             Redis With the RedisSearch module pre-loaded…   17
webhippie/redis                  Docker images for Redis                         10                                      [OK]
s7anley/redis-sentinel-docker    Redis Sentinel                                  9                                       [OK]
insready/redis-stat              Docker image for the real-time Redis monitor…   8                                       [OK]
redislabs/redisgraph             A graph database module for Redis               8                                       [OK]
bitnami/redis-sentinel           Bitnami Docker Image for Redis Sentinel         8                                       [OK]
arm64v8/redis                    Redis is an open source key-value store that…   6
centos/redis-32-centos7          Redis in-memory data structure store, used a…   4
redislabs/redismod               An automated build of redismod - latest Redi…   4                                       [OK]
circleci/redis                   CircleCI images for Redis                       2                                       [OK]
frodenas/redis                   A Docker Image for Redis                        2                                       [OK]
runnable/redis-stunnel           stunnel to redis provided by linking contain…   1                                       [OK]
tiredofit/redis                  Redis Server w/ Zabbix monitoring and S6 Ove…   1                                       [OK]
wodby/redis                      Redis container image with orchestration        1                                       [OK]
cflondonservices/redis           Docker image for running redis                  0
xetamus/redis-resource           forked redis-resource                           0                                       [OK]
```

untuk menjalankan dilatar belakang

gunakan perintah ```docker run -d redis```

```
$ docker run -d redis
a2dd792900f9ef6e5d2922bc446f87a2c8df34d0560ce4f2c372a7850ead0710
```