# docker_windows
  
  
### Notes
  
Pull the docker image
```bash
docker pull mcr.microsoft.com/windows/servercore:1607
```
  
Run the docker container
```bash
docker run -it mcr.microsoft.com/windows/servercore:1607 cmd.exe
```
  
Chef the conainer id
```bash
PS C:\Users\chef> docker ps
CONTAINER ID        IMAGE                                       COMMAND             CREATED             STATUS              PORTS               NAMES
1c2fbc032c20        mcr.microsoft.com/windows/servercore:1607   "cmd.exe"           32 minutes ago      Up 32 minutes                           berserk_hypatia
```
