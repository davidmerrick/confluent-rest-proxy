Demo of Dockerized Confluent REST proxy

# Usage:

Create a `.env` file and configure your bootstrap servers:
```shell
BOOTSTRAP_SERVERS=yourServersHere
```

Invoke this command:
```shell
docker-compose up
```

Test that it's running by making a GET to
```shell
 http://localhost:8082/topics
```

# Reference

[Confluent tutorial](https://docs.confluent.io/platform/current/tutorials/examples/clients/docs/rest-proxy.html)
