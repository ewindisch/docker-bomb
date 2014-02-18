Docker Bomb
-----------

This is the equivalent of a docker fork-bomb using docker-in-docker.

Howto:
------
```
docker run -v /var/lib/docker -privileged -lxc-conf=aa_profile=unconfined -t -i ewindisch/docker-bomb
```
