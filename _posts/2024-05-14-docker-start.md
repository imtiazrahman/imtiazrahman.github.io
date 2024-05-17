---
layout: default
title:  "Docker start/stop/kill"
date:   2024-05-14 14:30:00 +0600
---
### Docker start/stop/kill

You can stop a running container and similarly you can start a stop container. We now have some stop containers in our system. Find the list of the stopped container by docker ps – a command. From that list you can start your container. Type the below command to start a stop container.

```
docker start <contaierid/names>
```

If you want to stop or kill the container you can stop it by typing the below command.

```
docker stop/kill <contaierid/names>
```

The stop command sends a shutdown signal to the container. It will try to shut down the container in a proper way. The kill command sends a kill signal to the container which then immediately kill the container. kill is faster than stop.
