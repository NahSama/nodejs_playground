# Load balancer
Use haproxy for load balancing 4 express containers

## Commands
To build the Express application image
> 
    docker build -t nodeapp .

To run every containers
> 
    docker-compose up

To stop all the containers
> 

    docker-compose down