Docker Alpine openrc
====================

This Dockerfile can build containers capable to use openrc.

[![alpine build status](https://github.com/buluma/docker-alpine-openrc/actions/workflows/build-push-action.yml/badge.svg)](https://github.com/buluma/docker-alpine-openrc/actions/workflows/build-push-action.yml)

Branches
--------

This repository has multiple branches that relate to Alpine versions.

|Branch |Alpine Version|Docker image tag|
|-------|--------------|----------------|
|master |3             |3               |
|edge   |edge          |edge            |

Pull strategy
-------------

The different branches are **not** merged, they live as individual branches.

Manually starting
-----------------

```
docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:ro \
  buluma/alpine
```
