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
