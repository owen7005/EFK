# EFK

## Version
* Elasticsearch: 7.0.0
* Kibana: 7.0.0
* Fluentd: 1.4.2

## Quick Start


### Start 
```
docker-compose up -d elasticsearch
docker-compose up -d kibana
docker-compose up -d fluentd
docker-compose up -d backend
```

### request application with curl
```
curl http://localhost:5678
```

### screenshot

![](https://github.com/vqiu/EFK/blob/master/screenshot/kibana-7.png)
