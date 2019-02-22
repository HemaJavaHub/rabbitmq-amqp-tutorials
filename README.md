# rabbitmq-amqp-tutorials

## Demo, Part 1 - Introduction
Install RabbitMQ first...

https://www.rabbitmq.com/download.html

Then run Part 1 of the demo at...

https://www.rabbitmq.com/tutorials/tutorial-one-spring-amqp.html

To run the sender:
```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=hello-world,sender
```

To run the receiver:

```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=hello-world,receiver
```

## Demo, Part 2 - Work Queues

Part 2 of the demo...

https://www.rabbitmq.com/tutorials/tutorial-two-spring-amqp.html
