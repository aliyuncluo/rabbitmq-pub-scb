# rabbitmq-pub-scb
rabbitmq消息的发布与订阅模式

rabbitmq的消息的发布与订阅模式,即交换机类型为fanout。
交换器中没有路由键的概念，它会把消息发送到所有绑定在此交换器上面的队列中。

![图片说明](https://github.com/aliyuncluo/rabbitmq-pub-scb/blob/master/python-three-overall.png)
