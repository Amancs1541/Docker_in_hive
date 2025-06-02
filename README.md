# Docker_in_hive

# You need to make directory

## Command 
    mkdir <Name>
    cd <Name>
# The docker-compose.yml is given in the Repo

sudo docker compose up -d

#--------------------------------------------#
#Some essential Commands


docker logs <Dockername> #for checking logs
sudo ss -tunlp # checking open ports

sudo docker ps #checking Running process
sudo docker images #Currently Having Images

sudo docker exec -it <dockername> /bin/sh #Internactive Mode 

sudo docker restart <Name> # to restart 

sudo docker compose up -d #to Start Building Docker file


docker ps -q | xargs -r docker stop && docker ps -a -q | xargs -r docker rm #to stop and remove all running docker 
