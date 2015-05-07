#### PHP RabbitMQ Examples
Some examples from the official tutorial about RabbitMQ and PHP

-

**Example 1:** Runs one producer and one consumer. Simple hello world using RabbitMQ and PHP.

```
curl -sS https://getcomposer.org/installer | php
cd 1-producer-and-1-consumer
php ../composer.phar install
php send.php
php receive.php
```





--
I'm using [Alvaro Videla's](https://github.com/videlalvaro) **PHP-AMQPLib** on these examples:

[https://github.com/videlalvaro/php-amqplib](https://github.com/videlalvaro/php-amqplib)
