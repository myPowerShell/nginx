
# Running docker app and proxy with Nginx

sudo docker-compose build
sudo docker-compose up


# Checking inside containers
docker-container ps
docker-container exec proxy sh

# to see what is mounted inside container
mount

# increasing number of containers
docker-compose scale app=4
