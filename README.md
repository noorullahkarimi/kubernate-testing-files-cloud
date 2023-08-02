
# Kubernate config

## Project description

This project is just for the kubernate learning. it is config for microservice.

##  Directory structure

The files with suffix `service`, are for connection the pods and containers together.
The files with suffix `development`, are for creating the pods and developments.

## How to run :

The service clouds like `google cloud` or `play-with-k8s.com` or your server, it can run.
clone these files into your service, and run like this below: 
for files with suffix `deployment` write this command: 
`kubstl create -f redis-deployment.yml` and do for others also.
for files with suffix `service` write this command: 
`kubctl create -f redis-service.yml` and do for others also.


###  Prerequisites

just you should have server or install virtualbox on your laptop and create 5 nodes, then create a master node for it, put this on the node master and run or  `google cloud` or `play-with-k8s.com`.
