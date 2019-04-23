Build a docker image from Dockerfile.

```
$ docker build -t solr4 .
```

Name the image using tag subcommand.

```
$ docker tag solr4 okaday/solr4
```

`latest` label is default, Otherwise, the following label of versioning if you need it.

```
$ docker tag solr4 okaday/solr4:v1
```

Sign into docker hub, before push.

```
$ docker login
```

Push the image into docker hub.

```
$ docker push okaday/solr4
```
