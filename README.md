# kafka
Example for kafka producers/consumers

```docker-compose up -d```

Creates a topic called "teste"

```kafka-topics --create --topic=teste --bootstrap-server=localhost:9092 --partitions=3 --replication-factor=1```

Creates a consumer for the given "teste" topic

```kafka-console-consumer --topic=teste --bootstrap-server=localhost:9092```

Creates a producer for the given "teste" topic

```kafka-console-producer --bootstrap-server=localhost:9092 --topic=teste```
