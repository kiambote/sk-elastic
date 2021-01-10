# sk-elastic
The goal of this project is to smartly scale (Vertically and Horizontally) up and down a RTMP cluster according to the traffic.

### Scaling
It is a docker swarm cluster that is orcherstaing a RTMP Streaming server on top of Digital Ocean Droplets\
or any other cloud provider.

This app should be able to understand how to scale, vertical scale is going to depend on the amount of containers,\
the number of containers is part of the input. And the horizontal scale is going to depend on resources of the nodes that running.
