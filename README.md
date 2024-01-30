# RabbitMQ

RabbitMQ is an open-source message-broker software (sometimes called message-oriented middleware) that originally implemented the Advanced Message Queuing Protocol (AMQP) and has since been extended with a plug-in architecture to support Streaming Text Oriented Messaging Protocol (STOMP), MQ Telemetry Transport (MQTT), and other protocols.

wikipedia.org/wiki/RabbitMQ

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/71/RabbitMQ_logo.svg/1024px-RabbitMQ_logo.svg.png" width="80%" height="auto">

## How to use this Makejail

```sh
appjail makejail \
    -j rabbitmq \
    -f gh+AppJail-makejails/rabbitmq \
    -o virtualnet=":<random> default" \
    -o nat
```

## Arguments

* `rabbitmq_tag` (default: `13.2`): See [#tags](#tags).

## Tags

| Tag     | Arch    | Version        | Type   |
| ------- | ------- | -------------- | ------ |
| `13.2`  | `amd64` | `13.2-RELEASE` | `thin` |
| `14.0`  | `amd64` | `14.0-RELEASE` | `thin` |
