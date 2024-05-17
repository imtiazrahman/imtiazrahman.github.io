---
layout: default
title:  "Run Ubuntu container with shell access"
date:   2024-05-13 15:30:00 +0600
---

### Run container with shell access

After download the Ubuntu image lets run a container and access that container using that image. Type the below command for create a running container.

```
docker run -it ubuntu bash
```

After running that command you will find yourself inside a running container. You can check the Ubuntu version by using the cat command.

```
cat /etc/lsb-release
```

Now let’s exit from the container shell. Type the exit command to exit from the container. Use the docker ps command to see the status of the container. Again, you will get an empty list. Do you know why?

* * *

### Exit from the container

Every time you run the docker run command docker creates a container and put you in that container. But when you exit from that container the container stops. That’s the reason every time you get an empty list with the docker ps command. If you exit from the container the container will stop, but we want to keep our container running. Once again run another container.

```
docker run -it ubuntu bash
```

The container should start and you are now inside that container. Type the below key sequences for exit from the container without stopping it.

```
Ctrl+pq
```

Now check the docker ps command again. There should be a running container now.
