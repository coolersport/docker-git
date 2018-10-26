# docker-git
Git command as a docker image

##### How to

    docker run -u $(id -u):$(id -g) -v "$PWD":/git:z --rm -it coolersport/git clone
