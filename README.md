# Setup Mongodb in cluster mode
This sample demonstrates to setup mongodb in a cluster mode. 1 Primary and 2 Secondary nodes


# Setup
* Clone the repo
* Execute
    ```
    docker stack deploy -c docker-compose.yaml mongo-cluster
    ```
* Connect to one of the node and execute replicatset script in mongo shell