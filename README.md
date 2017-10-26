# docker-vagrant-multiple
basig template for multiple vagrant machines installing the docker service and building a swarm cluster

1. clone this project
2. customize Vagrantfile
3. customize ansible
4. run

```
vagrant box update
vagrant up
```

the content inside docker-images will be mounted into /home/ubuntu/docker-images
