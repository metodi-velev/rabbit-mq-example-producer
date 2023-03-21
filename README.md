# rabbit-mq-example-producer
RabbitMQ Messages Producer Example
<hr>
Run RabbitMQ in docker container: <br>
<code>
docker run -d -it --hostname my-rabbit --name some-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management
</code>
<br><br>
Messeges are consumed by <a href="https://github.com/metodi-velev/rabbit-mq-example-consumer" target="_blank">Consumer</a>
