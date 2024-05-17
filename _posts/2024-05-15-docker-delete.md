---
layout: default
title:  "Docker delete"
date:   2024-05-15 14:30:00 +0600
---
### Delete the container

After running some busybox container you are going to have a lot of stop container. To remove those containers run the below command:

```
docker rm container_id/container_name
```

To delete all the container all at a times type the below command:

```
docker rm $(docker ps -a -f status=exited -q)
```

### Delete docker image

You can delete docker images from your docker host by typing the below command

```
docker rmi <imagename>
```

