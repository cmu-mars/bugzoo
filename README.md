# BugZoo

Used to provide a BugZoo configuration for Phase II CP2 in the form of a
Docker container image (`cmumars/bugzoo`). The Docker image provided by this
repository is used as a way to avoid dynamically mounting the BugZoo
configuration files at run-time via docker-compose.

The Docker image for this BugZoo configuration should be automatically built
and tagged by DockerHub on each commit to `master`. If you wish to build the
Docker image manually, you may do so by executing the following command:

```
$ docker build -t cmumars/bugzoo .
```
