## Quick Start

To deploy an example HDFS cluster, run:
```
docker-compose up
docker exec -it NAMENODE_CONTAINER_NAME bin/bash
cd home
hdfs dfs -put src/ /
```
To enter jupyter, run:
```
docker exec -it JUPYTER_CONTAINER_NAME bash
jupyter server list
```
To to play tictactoe, run:
```
docker exec -it TICTACTOE_CONTAINER_NAME bash
cd src/tictactoe
python start_game.py
```


