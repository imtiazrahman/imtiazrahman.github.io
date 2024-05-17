---
layout: default
title:  "Docker Installation"
date:   2024-05-10 14:30:00 +0600
---
### Docker installation

Docker comes with two edition ce (Community Edition) and ee (Enterprise Edition).  Community edition is the free edition which we will use in this tutorial. I ll use an ubuntu 18.04 LTS server for this lab.

Type the below command to install the docker-ce in your host.

```
curl -fsSL get.docker.com -o get-docker.sh
```

this will download a script called “get-docker.sh” in your current directory. Type the below command to run the script which will install the docker-ce in your host.

```
sudo sh get-docker.sh
```

after the installation run the below command. The command will add your current user to the docker group so that you can run docker commands without sudo privileges.

```
sudo usermod -aG docker your-user
```

After that, run the following command to check then docker version

```
docker –-version
```

or

```
docker version
```
