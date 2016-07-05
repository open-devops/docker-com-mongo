# docker-com-mongo
Mongodb image for Open DevOps Pipeline

#docker pull
docker pull devopsopen/docker-com-mongo

#docker run
docker run -d -p 27017:27017 --name mongo devopsopen/docker-com-mongo

#using
setting the environment variables as following example:

export PATH=$PATH:/usr/devops/mongodb/bin

Then using mongo for operating
[root@host142 ~]# mongo
MongoDB shell version: 3.2.6
connecting to: test
Server has startup warnings:
...
>
