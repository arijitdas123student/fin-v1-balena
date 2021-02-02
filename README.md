# fin-v1-balena

Fork it and run using the following commands 

``docker build -t arijitdas123student/fin-v1-balena``

Here is an example of the same 

`` $ docker build -t svendowideit/ambassador .``

``Sending build context to Docker daemon 15.36 kB``

``Step 1/4 : FROM alpine:3.2``

 ``---> 31f630c65071``
 
``Step 2/4 : MAINTAINER SvenDowideit@home.org.au``

 ``---> Using cache``
 
 ``---> 2a1c91448f5f``
 
``Step 3/4 : RUN apk update &&      apk add socat &&        rm -r /var/cache/``

 ``---> Using cache``
 
 ``---> 21ed6e7fbb73``
 
``Step 4/4 : CMD env | grep _TCP= | (sed 's/.*_PORT_\([0-9]*\)_TCP=tcp:\/\/\(.*\):\(.*\)/socat -t 100000000 TCP4-LISTEN:\1,fork,reuseaddr TCP4:\2:\3 \&/' && echo wait) | sh``

 ``---> Using cache``
 
 ``---> 7ea8aef582cc``
 
``Successfully built 7ea8aef582cc ``
