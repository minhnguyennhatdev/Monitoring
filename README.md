### ***Some Exporters Need Specific Config Or User's Privileges*** 
### *Please Read Documents For Detail*  

## DOCUMENTS
- [mysql-exporter](https://github.com/prometheus/mysqld_exporter) *(Need user privileges)*  
- [mongodb-exporter](https://github.com/percona/mongodb_exporter) *(Need user privileges)*  
```
use yourdb
db.createUser({
    "user": "moniter",
    "pwd": "", // password
    "roles": [
        {
            "role": "clusterMonitor",
            "db": "admin"
        },
        {
            "role": "read",
            "db": "local"
        }
    ]
})
```
- [redis-exporter](https://github.com/oliver006/redis_exporter)  
- [elasticsearch-exporter](https://github.com/prometheus-community/elasticsearch_exporter)  
- [kafka-exporter](https://github.com/danielqsj/kafka_exporter)  