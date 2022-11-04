# Confluent kafka for streaming data
Kafka is primarily used to build real-time streaming data pipelines and applications that adapt to the data streams. 

### Sample Code
The repo contains sample code to Produce data to Confluent Kafka and Consume data from Confluent Kafka.

### Kafka Configuartion:

Get the following details from kafka.
1. API_KEY
2. API_SECRET_KEY
3. BOOTSTRAP_SERVER
4. SCHEMA_REGISTRY_API_KEY
5. SCHEMA_REGISTRY_API_SECRET
6. ENDPOINT_SCHEMA_URL

### Flows

1. Producer

* starting_point: producer_main.py 
* Updating data in kafka

2. Consumer

* starting_point: consumer_main.py 
* Consume data from kafka and update in mongodb.

