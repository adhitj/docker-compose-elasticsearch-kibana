# **docker-compose-elasticsearch-kibana**

# **Overview**
- [x] 3 Node Elasticsearch version 7.1.1
- [x] Kibana version 7.1.1
- [x] APM Server version 7.1.1
- [x] NGINX

# **COMING UP DOCKER APPLICATION PACKAGE FOR SWARM**

## **Requirements**
- [x] Docker 18.05
- [x] Docker-compose 1.21

### **Start Stack in Daemon Mode**
```
docker-compose up -d
```

### **Check status of docker-compose cluster**
```
docker-compose ps -a
```

### **Stop Compose Stack**
```
docker-compose down
```

### **Cluster Node Info**
```
http://localhost:9200/_nodes?pretty=true
```

### **Access Kibana**
```
http://localhost:5601
```

### **Accessing Kibana through Nginx**
```
http://localhost:8080
```

### **Access Elasticsearch**
```
http://localhost:9200
```

