# docker_windows
  
  
### Notes
  
#### Windows 2019
  
Run the docker container
```bash
docker run mcr.microsoft.com/windows/servercore:ltsc2019
```
  
Your output will look like this:
```bash
C:\Users\chef>docker run mcr.microsoft.com/windows/servercore:ltsc2019
Unable to find image 'mcr.microsoft.com/windows/servercore:ltsc2019' locally
ltsc2019: Pulling from windows/servercore
4612f6d0b889: Pull complete
c3aff4450246: Pull complete
Digest: sha256:0197a95621a4dc47eb5635f664459a86ec7110d04a99438a54af77bd982487ec
Status: Downloaded newer image for mcr.microsoft.com/windows/servercore:ltsc2019
Microsoft Windows [Version 10.0.17763.1457]
(c) 2018 Microsoft Corporation. All rights reserved.

C:\Users\chef>
```
  
Scan your container with Chef InSpec
```bash

```
  
#### Windows 2016
  
Pull the docker image
```bash
docker pull mcr.microsoft.com/windows/servercore:1607
```
  
Run the docker container
```bash
docker run -it mcr.microsoft.com/windows/servercore:1607 cmd.exe
```
  
Check the conainer id with the `docker ps` command
```bash
PS C:\Users\chef> docker ps
CONTAINER ID        IMAGE                                       COMMAND             CREATED             STATUS              PORTS               NAMES
1c2fbc032c20        mcr.microsoft.com/windows/servercore:1607   "cmd.exe"           32 minutes ago      Up 32 minutes                           berserk_hypatia
```
