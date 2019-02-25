# rabbitmq-amqp-tutorials

### Tutorial 1

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

###### Tutorial 1

https://www.rabbitmq.com/tutorials/tutorial-one-spring-amqp.html

To run the sender:
```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=hello-world,sender
```

To run the receiver:

```
java -jar build/libs/rabbitmq-amqp-tutorials-1.0.0.jar --spring.profiles.active=hello-world,receiver
```

###### Tutorial 2

https://www.rabbitmq.com/tutorials/tutorial-two-spring-amqp.html

###### Tutorial 3

https://www.rabbitmq.com/tutorials/tutorial-three-spring-amqp.html

###### Tutorial 4

https://www.rabbitmq.com/tutorials/tutorial-four-spring-amqp.html

###### Tutorial 5

https://www.rabbitmq.com/tutorials/tutorial-five-spring-amqp.html

###### Tutorial 6

https://www.rabbitmq.com/tutorials/tutorial-six-spring-amqp.html
