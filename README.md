# resin-php-hello-world

This is a barebone resin.io project to demonstrate running PHP code. This project aims to allow our builders to build containers for multiple architectures from one code repository, by implementing simple [Dockerfile templates](https://docs.resin.io/deployment/docker-templates/).

```
FROM resin/%%RESIN_MACHINE_NAME%%-debian
```

For an explanation of how [resin.io](https://resin.io/) uses Dockerfiles check out the [Dockerfile guide](https://docs.resin.io/deployment/docker-templates/). Additionally, if you want to learn how to optimise your Dockerfile, check out [Optimise your Build](https://docs.resin.io/deployment/build-optimisation/).
