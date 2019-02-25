# RabbitMQ Tutorials

RabbitMQ is a message broker: it accepts and forwards messages. You can think about it as a post office: when you put the mail that you want posting in a post box, you can be sure that Mr. or Ms. Mailperson will eventually deliver the mail to your recipient. In this analogy, RabbitMQ is a post box, a post office and a postman.

The major difference between RabbitMQ and the post office is that it doesn't deal with paper, instead it accepts, stores and forwards binary blobs of data ‒ messages.

These tutorials will take you through 6 different ways of using the RabbitMQ message queue.

###### Install Erlang

https://www.rabbitmq.com/which-erlang.html

On Mac
```
brew install erlang
```

On Windows
```
scoop install erlang
```
###### Install RabbitMQ

https://www.rabbitmq.com/download.html

## Tutorial 1

https://www.rabbitmq.com/tutorials/tutorial-one-spring-amqp.html

###### Build Application

Using the terminal tab:
```
gradle clean assemble
```
###### Run Application

To run the sender:
```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=hello-world,sender
```

To run the receiver:

```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=hello-world,receiver
```

## Tutorial 2

https://www.rabbitmq.com/tutorials/tutorial-two-spring-amqp.html

###### Build Application

Using the terminal tab:
```
gradle clean assemble
```
###### Run Application

To run the sender:
```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=work-queues,sender
```

To run the receiver:
```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=work-queues,receiver
```

## Tutorial 3

https://www.rabbitmq.com/tutorials/tutorial-three-spring-amqp.html

###### Build Application

Using the terminal tab:
```
gradle clean assemble
```
###### Run Application

To run the sender:
```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=pub-sub,sender --tutorial.client.duration=60000
```

To run the receiver:
```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=pub-sub,receiver --tutorial.client.duration=60000
```

## Tutorial 4

https://www.rabbitmq.com/tutorials/tutorial-four-spring-amqp.html

###### Build Application

Using the terminal tab:
```
gradle clean assemble
```
###### Run Application

To run the sender:
```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=routing,sender --tutorial.client.duration=60000
```

To run the receiver:
```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=routing,receiver --tutorial.client.duration=60000
```

## Tutorial 5

https://www.rabbitmq.com/tutorials/tutorial-five-spring-amqp.html

###### Build Application

Using the terminal tab:
```
gradle clean assemble
```
###### Run Application

To run the sender:
```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=topics,sender --tutorial.client.duration=60000
```

To run the receiver:
```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=topics,receiver --tutorial.client.duration=60000
```

## Tutorial 6

https://www.rabbitmq.com/tutorials/tutorial-six-spring-amqp.html

###### Build Application

Using the terminal tab:
```
gradle clean assemble
```
###### Run Application

To run the server:
```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=rpc,server --tutorial.client.duration=60000
```

To run the client:
```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=rpc,client
```
