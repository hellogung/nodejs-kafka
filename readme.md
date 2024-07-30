# How to Run

## 1. Install Dependencies
```shell
npm install
```

## 1. Run Kafka
```shell
kafka-server-start config/kraft/server.properties
```
## 2. Run Consumer
```shell
node consumer.js
```

## 3. Run Producer
```shell
node producer.js
```