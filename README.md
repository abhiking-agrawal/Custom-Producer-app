# Custom-Producer-app
Big data messaging with Kafka

 1. In a Git Bash window, Go to "Custom-Producer-app\KafkaAPIClient" folder compile the code using Maven and create an executable jar file with  mvn clean compile assembly:single

 2. In this Git Bash window, start the Consumer app using topic test and group1 with 
> java -cp target/KafkaAPIClient-1.0-SNAPSHOT-jar-with-dependencies.jar com.spnotes.kafka.simple.Consumer test group1

 3. In another Git Bash window, Go to "Custom-Producer-app\KafkaAgrawal" folder compile the code using Maven and create an executable jar file with  mvn clean compile assembly:single  and then start the Producer app using topic test with
> java -cp target/KafkaAgrawal-1.0-SNAPSHOT-jar-with-dependencies.jar edu.nwmissouri.dis.agrawal.kafka.CustomProducer test

4. Producer window will show the randomely generated strings.

5. Verify the messages are output by the Consumer.

