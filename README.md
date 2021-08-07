# MyCustomOS


Im just making this as a test to see if I can do and how well it will work
Im also using the [Youtube](https://www.youtube.com/watch?v=FkrpUaGThTQ&list=PLZQftyCk7_SeZRitx5MjBKzTtvk0pHMtp) tutorial as to help me make one


Stuff you will need
-------------------
git, docker, a docker container, QEMU,


If you choose to edit this os at all, make sure to enable the docker container (if it hasn't already).
Do
`docker buildenv -t nameofthing-buildenv`
to start the docker container do 
`docker run --rm -it -v $pwd:/root/env name of docker container` (on Linux/Mac)
If you are on windows do 
`docker run --rm -it -v %cd%:/root/env name of docker container`