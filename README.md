#### UPDATE MONGO USER ROLE

### Permissions
Connecting user should have sufficient rights to query needed stats:

```
   {
      "role":"clusterMonitor",
      "db":"admin"
   },
   {
      "role":"read",
      "db":"local"
   }
```



#### DOCUMENTS

[mysql-exporter](https://github.com/prometheus/mysqld_exporter)
[mongodb-exporter](https://github.com/percona/mongodb_exporter)
[redis-exporter](https://github.com/oliver006/redis_exporter)
[elasticsearch-exporter](https://github.com/prometheus-community/elasticsearch_exporter)