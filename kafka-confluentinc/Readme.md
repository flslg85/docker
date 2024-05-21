# kafka-confluentinc

### doker 외부 접속(localhost 에서 접속)
- zookeeper
  - host: localhost
  - port: 22181
  - chroot path: /
- bootstrap servers
  - localhost:29092

### docker 내부 접속
- zookeeper
  - zookeeper:2181
- bootstrap servers
  - kafka:9092
