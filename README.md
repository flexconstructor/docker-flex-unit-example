# docker-flex-unit-example
Simple flex project for builds and tests into docker container. 
Use gradle with gradleFX plugin for build and test your flex/as3 application in docker container.
I think this is a good solution for the implementation of application test in a CI server.
#Usage:
Docker demon must been running!
Run:
````
$ gradle build

````
for builds and tests your flex project.

More info about 'flexconstructor/docker-flexunit' docker container:
[link](https://hub.docker.com/r/flexconstructor/docker-flexunit/)
