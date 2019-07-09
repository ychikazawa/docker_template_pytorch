# Pytorch Docker template

This is a Docker template that provides an environment with Pytorch.

## Requirement

- [Docker](https://www.docker.com/)
  - docker-compose
- [nvidia-docker 2](https://github.com/nvidia/nvidia-docker/wiki/Installation-(version-2.0))

## Usage

Run Jupyter notebook:

```console
$ docker-compose up
```

Go to `http://localhost:8888` and you'll see the notebooks.

## Install

Clone repository:

```console
$ git clone https://github.com/PiroHiroPiro/docker_template_pytorch.git
$ cd docker_template_pytorch
```

Build image:

```console
$ cp .env.example .env
$ docker-compose build
```

## Licence

This software is released under the MIT License, see [LICENSE](https://github.com/PiroHiroPiro/docker_template_pytorch/blob/master/LICENSE).

## Author

[Hiroyuki Nishizawa](https://github.com/PiroHiroPiro)
