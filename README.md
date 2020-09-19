# Docker compose files

list of docker files that I can use daily

## most of the bd containers works with:

- **username: root**
- **password: root**

## os:

- alpine very interesting maybe watch such wow

## notes for me le dumb

- to run a docker-compose file just use ```docker-compose up``` with ```-d```it will launch in daemon mode that way it doesn't need the current term to be open to be alive
- to build a docker image with a ```Dockerfile``` you must launch ```docker build .``` with optionnal ```--tag NameTag``` in order to stick a tag on this build
- diff between a docker-compose and a Dockerfile is that docker-compose is for setting up a multiple containers env, while a Dockerfile is when you want to specify the build of a specific image.