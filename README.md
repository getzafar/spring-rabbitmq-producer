Start RabbitMQ with this command-

docker run -d --hostname my-rabbit --name some-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management


Start spring-rabbitmq-producer


Send a POST request to http://localhost:9000/publish

{
    "message": "This is a new message 4"
}


RabbitMQ can be accessed on http://localhost:15672/
default username/password- guest


Start spring-rabbitmq-producer to consume
