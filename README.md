#### PHP RabbitMQ Examples
Some examples from the official tutorial about RabbitMQ and PHP

-

**Install:**
```
curl -sS https://getcomposer.org/installer | php
php ../composer.phar install
```
-

**Example 1:** Runs one producer and one consumer. Simple hello world using RabbitMQ and PHP.

```
cd 1-producer-and-1-consumer
php send.php
php receive.php
```

**Example 2:** Runs one producer and two consumers. Distributing tasks among workers 

```
cd 1-producer-and-2-consumers
php new_task.php
php worker.php
```


--
I'm using [Alvaro Videla's](https://github.com/videlalvaro) **PHP-AMQPLib** on these examples:

[https://github.com/videlalvaro/php-amqplib](https://github.com/videlalvaro/php-amqplib)
