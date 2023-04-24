# Useful Linux Commands

## BASH

### make a directory and cd into it
```mkdir <name> && cd $_```

### execute .sh file
```chmod +x <filename.sh>```
```./<filename.sh>```



## DOCKER

### show all docker containers 
```docker ps -a```

### stop all docker containers
```docker stop $(docker ps -a -q)```

### remove all docker containers
```docker remove -f $(docker ps -a -q)```