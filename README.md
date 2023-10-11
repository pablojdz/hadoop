### Deploy Hadoop cluster using Docker
Run the docker containers
-> docker-compose up -d

Accessing the UI
-> The Namenode UI can be accessed at http://localhost:9870/ and the ResourceManager UI can be accessed at http://localhost:8088/

Accessing the NameNode
-> docker exec -it namenode bash 