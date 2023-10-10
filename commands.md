# Main commands

+ `sudo usermod -aG docker $USER`
    + creates a usermod that  every time docker is used sudo will be use too.

+ `docker run IMAGE`
    + docker is runs an image. This mean docker finds an image in docker hub, dowload, verifies with a command and execute.

+ `docker pull IMAGE`
    + docker only donwloads an image.

+ `docker ps` or `docker container ls`
    + show if any container is running.

+ `docker ps -a` or `docker container ls -a`
    + show all containers.

+ `docker stop -t=0 [CONTAINERID or NAMES] `
    + stops an active container. t=0 reducese to 0 time for stops a container.

+ `docker start [CONTAINERID or NAMES]`
    + activated an container.

+ `docker exec -it [CONTAINERID or NAMES] COMMAND`
    + interacts with container; i -> interactive; t -> terminal.

+ `docker pause [CONTAINERID or NAMES]`
    + pauses a container.

+ `docker unpause [CONTAINERID or NAMES]`
    + unpause a container.

+ `docker rm [CONTAINERID or NAMES]`
    + removes a docker containers.

+ `docker run -it IMAGE COMMAND`
    + iterates with this container but if there is no procecss, kill it.

+ `docker run -d IMAGE`
    + runs an image and stops terminal from freezing it.

+ `docker rm [CONTAINERID or NAMES] --force`
    + stops container and remove it.

+ `docker run -d -P IMAGE`
    + runs an image and stops terminal from freezing it and changes de port to automaic form.

+ `docker port [CONTANINERID or NAME]`
    + changes de port of virtual container to port for os sistem.

+ `docker run -d -p 8080:80 IMAGE`
    + runs an image and stops terminal from freezing it and changes virtual port (80) to a os port (8080) form.
    