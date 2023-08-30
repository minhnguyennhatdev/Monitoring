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


