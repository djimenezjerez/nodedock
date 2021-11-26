# Nodedock

This template should help get you to start to developing with Node inside a Docker container.

## Setup

* Install [https://git-scm.com/book/en/v2/Getting-Started-Installing-Git][Git], [https://docs.docker.com/engine/install/][Docker] and [https://docs.docker.com/compose/install/][Docker Compose] as instructed in their documentations.

* Clone the project inside your Javascript app code:

```sh
$ git clone https://github.com/djimenezjerez/nodedock.git
```

* Enter into directory:

```sh
$ cd nodedock
```

* Copy the environment file and edit this according to your needs:

```sh
$ cp .env.example .env
```

* Build the image:

```sh
$ docker compose build workspace
```

* Start the container:

```sh
$ docker compose up -d workspace
```

* Enter the container and enjoy development:

```sh
$ docker compose exec --user node workspace bash
```
