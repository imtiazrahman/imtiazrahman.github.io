---
layout: default
title:  "Docker images"
date:   2024-05-12 16:30:00 +0600
---

### Docker images

As you already know that the container are images based and we already run some container. You can find the image information of those containers by typing the below command:

```
docker images
```

This will give you the list of downloaded images while running the container.


### Download docker image

Docker download the respective image during the runtime of a container, but you can download your desire image if you want. You can also perform a search for the specific image. Type the below command to see a list of images docker have in its online repository docker hub. Let’s try to search the ubuntu image.

```
docker search ubuntu
```

You will see a list of Ubuntu images available online on docker hub. After getting your desire image it’s time to download that image. Type the below command to download the Ubuntu image.

```
docker pull ubuntu
```

The command will download the Ubuntu latest image available in docker hub. Check the newly downloaded image in your local repository. Again type the below command to see the local image list.

```
docker images
```

This will give you locally download image. if you want to learn more about your downloaded image then type the below command.

```
docker image inspect ubuntu
```

You will find the detail information about the image.
