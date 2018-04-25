# cloud-demo
mvn clean package
java -jar target/cloud-demo-1.0-SNAPSHOT.jar --spring.profiles.active=peer1
java -jar target/cloud-demo-1.0-SNAPSHOT.jar --spring.profiles.active=peer2
java -jar target/cloud-demo-1.0-SNAPSHOT.jar --spring.profiles.active=peer3
java -jar target/cloud-demo-1.0-SNAPSHOT.jar --spring.profiles.active=peer4
java -jar target/cloud-demo-1.0-SNAPSHOT.jar --spring.profiles.active=peer5
java -jar target/cloud-demo-1.0-SNAPSHOT.jar --spring.profiles.active=peer6