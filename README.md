# How to program execution
1.docker-compose up -d

2.docker exec -it python /bin/bash

3.python main.py 

# build and run
docker-compose up -d

# container connect
docker exec -it python /bin/bash

# remove
docker-compose down --rmi all

# How to add library
When adding a library please describe the necessary item in requirements.txt and rebuild


# start
docker-compose start

# restart
docker-compose restart 

# stop
docker-compose stop
