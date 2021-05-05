# Kafka Lab 

Start Kafka and wait until it's ready: 

```
docker-compose up -d kafka
```

Produce some events: 

```
docker-compose up producer
```

Consome them: 

```
docker-compose up consumer
```

## Resources

* [Kafka Quickstart](https://kafka.apache.org/quickstart)
* [Kafka Python client](https://github.com/confluentinc/confluent-kafka-python)
