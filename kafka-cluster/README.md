This is a basic Kafka project showing how to run a Kafka cluster udsing Docker.

It serves as a base for other project under the Kafka branch. It's solely used for my personal learning and interest.

## Geting started

Make sure you have docker running and docker-compose installed.

### To start the cluster

Go to the directory where the docker compose file is located and write

```
docker-compose up -d

```

this will run the cluser as a demon. If it's the first time docker-compose will build the different parts of the cluster.

When the cluser is running it can be accessed on the ports assigned int he docker compose file.

It's easy to add more nodes to the cluster.


### Stop the cluster

```
docker-compose down

```

### Accessing the cluster

Use offset explorer to access the cluster and work with messages and topics
