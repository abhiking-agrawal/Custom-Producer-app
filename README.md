# Custom-Producer-app
Big data messaging with Kafka

 1. In a Git Bash window, compile the code using Maven and create an executable jar file with  mvn clean compile assembly:single

 2. In this Git Bash window, start the Consumer app using topic test and group1 with 
> java -cp target/KafkaAPIClient-1.0-SNAPSHOT-jar-with-dependencies.jar
> com.spnotes.kafka.simple.Consumer test group1

 3. In another Git Bash window, start the Producer app using topic test with
> java -cp target/KafkaAPIClient-1.0-SNAPSHOT-jar-with-dependencies.jar
> com.spnotes.kafka.simple.Producer test

4. Type some messages for the Producer.

5. Verify the messages are output by the Consumer.

6. Plan and design a routine to create messages without the users typing. You may use an array of messages, generate them randomly, or access a public API.
  
7.  Implement your Custom Producer app.

8.  Start your app.

9.  Verify your messages are output by the Consumer.
