# program execution procedure
1.docker-compose up -d

2.docker exec -it python /bin/bash

3.python main.py 

# build and run
docker-compose up -d

# remove
docker-compose down --rmi all

# start
docker-compose start

# restart
docker-compose restart 

# stop
docker-compose stop

# container connect
docker exec -it python /bin/bash
