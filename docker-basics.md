#### What is Docker
```
```

* List running containers
```
docker ps -a

CONTAINER ID        IMAGE                             COMMAND                  CREATED             STATUS                    PORTS                      NAMES
dbws1c5fae27        <image-name>                      "/bin/sh -c 'cd /opt/"   2 days ago          Up 2 days                 8089/tcp                   docker-container-one
78he1fdd32af        <image-name>                      "/docker-entrypoint.s"   2 days ago          Up 2 days                 0.0.0.0:5411->5432/tcp     docker-container-two

```

* List docker images
```
docker images
```

* Accessing a container
```
docker exec -it <container-id> /bin/bash
```

* Stop container
```
docker stop <container-id>
```

* Remove container(make sure it is stoped)
```
docker rm <container-id>
```

* Remove docker images
```
docker rmi <image-id>
```

* Pull images
```
docker pull <image-name>
```
