# Elasticsearch Cluster

## Config
* config/elasticsearch.yml

  * master
```
cluster.name: elasticsearch
node.data: true
network.host: 0.0.0.0
discovery.zen.ping.unicast.hosts: ["127.0.0.1", "52.78.139.201"]
```

  * data nodes
```
cluster.name: elasticsearch
node.data: true
network.host: 0.0.0.0
discovery.zen.ping.unicast.hosts: ["127.0.0.1", "52.78.207.130"]
```

* Security Group
  * 9200
  * 9300
  * 9301


## Performance
* open files
`max file descriptors [4096] for elasticsearch process likely too low, consider increasing to at least [65536]`
