# hello-world-nodejs-docker

This is a basic example for a hello world nodejs app with Docker workflow 


## Getting Started

```
$ git clone https://github.com/ORzazade/hello-world-nodejs-docker.git

```

## Running on dev mode

Open a new terminal window, execute the following commands:

```
$ cd hello-world-nodejs
$ docker-compose up -d
```

After that, open http://localhost:3000 on your browser to see the app on the dev mode.

## Running on prod mode

Open a new terminal window,, `ssh` into the teracy-dev VM to execute the following commands:

```
$ cd hello-world-nodejs
$ docker-compose -f docker-compose.prod.yml up -d
```


## License

MIT, see the LICENSE file.
