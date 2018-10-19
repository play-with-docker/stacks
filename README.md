# Docker example stacks

This repository contains a curated list of stacks to showcase the docker images
available in the public docker registry.

You can simply grab the current examples and run them with [docker stack deploy](https://docs.docker.com/engine/reference/commandline/stack_deploy/) or [docker compose](https://docs.docker.com/compose/)
to have a fully functional environments.

## Submitting a new stack

To submit a stack just open a PR against this repo with the following folder structure:

`/<name>/<repository>/<tag>/<stack.yml>`

In the case of official repositories, `<name>` is not necessary. If you're submitting a new stack,
make sure the default name is `stack.yml`. 

When submitting new stacks it's important to find an intuitive way to showcase the example you're aiming at.
For example, if adding a stack for a DB, try to also add a web interface container so it's easier to play with it. 

## RFS (request for stacks)

This is a list of the stacks we would love to have here:

- [x] ~~registry~~
- [x] ~~prometheus~~
- [x] ~~jenkings~~
- [ ] rabbitmq
- [ ] memcached
- [ ] cassandra
- [ ] traefik
- [x] ~~ghost~~
- [ ] telegraf
- [ ] drupal
- [x] neo4j
- [ ] influxdb
- [ ] crate
- [ ] zookeeper
- [ ] etcd
- [ ] couchdb
- [ ] php
- [ ] rocket chat
