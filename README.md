# Distributed menu service
This is a National Chengchi Univercity Distributed Systems Project using Docker and Envoy Proxy.

In ```fronyenvoy.yaml```:
<br>
<img src="images/frontenvoy.png" alt="drawing" width="450"/>


Represents the follwoing struture:
<br>
<img src="images/structure.png" alt="drawing" width="450"/>

## Run the service

Start the Docker compose.

    docker-compose build --pull
    docker-compose up -d
    
Check the status of the containers.

    docker-compose ps

Scale up the service.

    docker-compose scale service1=3

Run the server.

    python3 service.py
