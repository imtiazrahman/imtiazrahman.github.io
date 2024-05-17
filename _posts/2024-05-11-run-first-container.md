---
layout: default
title:  "Run docker container"
date:   2024-05-11 14:30:00 +0600
---
### Run first container
You have successfully installed the docker-ce in your host now it’s time to run our first container. Type the below command to run the “hello-world” docker container.

```
docker run hello-world
```

you will see some activity in your screen. Keep patient and watch carefully. After sometime you will see a message like the below one:

```
Hello from Docker!
This message shows that your installation appears to be
working correctly.
```

And also some other message which simply describes what happen when you run the docker run command.

* * *

### The busybox container

Let’s run another container name “busybox”. You can pass any command during the runtime and it will give you the output of that command. Type the below command to run the busybox container.

```
docker run busybox echo "Hello docker"
```

you can pass any other command instead of echo command. Try to run the container again with other command you like.

