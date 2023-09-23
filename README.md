# open-interpreter-docker

[Open Interpreter](https://github.com/KillianLucas/open-interpreter) docker environment

## Setup

Execute following command:

```sh
$ cd && git clone https://github.com/s-hiraoku/open-interpreter-docker
```

### Docker build

```sh
$ cd ~/open-interpreter-docker
$ docker build -t open-interpreter ./
```

### Docker run

```sh
$ cd ~/open-interpreter-docker
$ docker run -it --rm -v $(pwd):/root open-interpreter
```

### Run app

Execute following command in container:

```sh
root@hostname:~# interpreter -y
```

And enjoy open interpreter

## References

- https://note.com/masia02/n/n630d091c4a02
- https://github.com/Frederic-Boulanger-UPS/docker-ubuntu_22-04-novnc
- https://rooter.jp/infra-ops/build_docker_jp_env/
