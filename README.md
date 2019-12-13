# springboot-kafka-example

## Reference
- https://www.youtube.com/watch?v=NjHYWEV_E_o
    - https://github.com/TechPrimers/spring-boot-kafka-producer-example
    
    
## Maven
```$xslt
<dependency>
    <groupId>org.springframework.kafka</groupId>
    <artifactId>spring-kafka</artifactId>
</dependency>
```


## Run
/bin/zookeeper-server-start.sh config/zookeeper.properties
/bin/kafka-server-start.sh config/server.properties

## Publish
http://localhost:8081/kafka/publish/Hello