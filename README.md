## Supported tags and respective Dockerfile links

<ul><li><a href="https://raw.githubusercontent.com/zhangddjs/docker-zookeeper/master/covfefezdd/zookeeper/latest/Dockerfile"><code>latest</code></a></li></ul>

## Installation from Docker registry hub

You can download the image with the following command:

```
docker pull covfefezdd/zookeeper
```

## Build by Dockerfile

You can build the image by Dockerfile with the following commands:

```
wget https://raw.githubusercontent.com/zhangddjs/docker-zookeeper/master/covfefezdd/zookeeper/latest/Dockerfile
wget https://raw.githubusercontent.com/zhangddjs/docker-zookeeper/master/covfefezdd/zookeeper/latest/zoo.cfg
wget https://raw.githubusercontent.com/zhangddjs/docker-zookeeper/master/covfefezdd/zookeeper/latest/docker-entrypoint.sh
docker build -t covfefezdd/zookeeper .
```

## Start to run

You can run the container with the following commands:

```
docker run --name zoo-server --restart always -p 30000:2181 -d covfefezdd/zookeeper
```
