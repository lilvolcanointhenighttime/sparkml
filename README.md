## Quick Start

To deploy an example HDFS cluster, run:
```
docker-compose up
docker exec -it NAMENODE_CONTAINER_NAME bin/bash
cd home
hdfs dfs -put kursovaya/ /
```
To enter jypiter, run:
```
docker exec -it JUPYTER_CONTAINER_NAME bash
jupyter server list
```


