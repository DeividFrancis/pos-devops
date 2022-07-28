provisionamento e deploy com vagrant

provisionamento e deploy com docker

Ambos deploy precisam ter uma aplicacao de exemplo e um banco de dados.
E livre a escolha da aplicacao e do banco de dados

limite 27/07

# Docker

```sh
$ docker compose up
```

acessa `http://localhost:80`

# Vagrant

```sh
$ vagrant up

$ vagrant ssh

$ cd /vagrant/src
$ npm i
$ npm start

```

acessa `http://localhost:3000`
