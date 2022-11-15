# ESTUDO_Kafka
ANDAMENTO - Estudo sobre a mensageria Kafka


$ kafka-topics.sh --create --bootstrap-server localhost:9092 --replication-factor 1 --partitions 1 --topic LOJA_NOVO_PEDIDO
$ kafka-topics.sh --list --bootstrap-server localhost:9092
$ kafka-console-producer.sh --broker-list localhost:9092 --topic LOJA_NOVO_PEDIDO
$ kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic LOJA_NOVO_PEDIDO --from-beginning
