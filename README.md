# RabbitMQ_RequestReply-QueueName-Demo

1.We first have to run RabbitMQ. Navigate to this path:

C:\Program Files\RabbitMQ Server\rabbitmq_server-3.11.0\sbin\
Then open a command prompt as Adminitrator and run the command:

rabbitmq-service start
Note: to stop the RabbitMQ service run the command

rabbitmq-service stop
2.Enter in RabbitMQ in the internet browser:

http://localhost:15672/

Username:guest

Password:guest

3.Create a new queue called "requests".

4.Create a new queue called "responses".

5.Set as startup projects both projects in the Visual Studio solution.

6.Build and run the solution.

![Request-Response-Pattern](https://github.com/luiscoco/RabbitMQ_RequestReply-QueueName-Demo/assets/32194879/650e8da9-603a-44f4-881b-453cf3b77fa4)
