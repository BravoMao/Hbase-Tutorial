# Hbase-Tutorial
A simple hbase tutorial 

Docker install
----------
https://docs.docker.com/docker-for-mac/install/

Pull a exist docker hbase image
----------
    $ docker pull dajobe/hbase

Run docker image
----------
To run HBase by hand:

    $ mkdir data
    $ id=$(docker run --name=hbase-docker -h hbase-docker -d -v $PWD/data:/data dajobe/hbase)

Start docker container
----------
    $ docker start hbase-docker

### Relevant articles

- [HBase with Java](http://www.baeldung.com/hbase)
