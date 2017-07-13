# NodePhantomjs-Centos7

selenium phantomjs node
phantomjs version: 2.0.0
fixed hub register bug
base OS: centos 7.2

Run with connect remote hub:

docker run -d -e HUB_ADDR=<hub IP> -e HUB_PORT=<hub port> -e NODE_PORT=<node port> -e IP=<node IP> -e PHANTOMJS_OPTS=<phantomjs options> -p <node port>:<node port> kenlma/nodephantomjs-centos7
