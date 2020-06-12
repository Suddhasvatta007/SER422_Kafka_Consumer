# SER422_Kafka_Consumer
Kafka Examples
This repository contains Consumer codes written in Java.

Please follow the steps in the exact same order as metioned to run the application inside this repo.

BEFORE RUNNING THE APPLICATION

Step 1: Download & install Kafka - Theoretically it works for all operating systems however I would suggest do it on a MAC or if you do not have a MAC system download a Linux VM. Go to this website https://kafka.apache.org/quickstart & follow the steps as mentioned.

Step 2: After step 1 you should have your Kafka server setup on your local system. Test it by sending messages (shown is the website as well).

Step 3: For writing a consumer we first need an IDE (any IDE of your choice), if you don't have one, I would recommend IntelliJ IDEA https://www.jetbrains.com/idea/download/#section=linux Download the free version as your operating system.The next task is to write a prdocuer. If you have not then please refer to this repo https://github.com/Suddhasvatta007/SER422_Kafka_Producer

Step 4: Setting up the IDE. For that use this video https://www.youtube.com/watch?v=bwXWIx5dZjw

RUNNING THE CONSUMER APPLICATION

Step 1: Clone this repo on to your local system using an IDE (recomended). However if you want you may not use it. If you face an error like "Error:java: error: release version 5 not supported" please go this website https://stackoverflow.com/questions/59601077/intellij-errorjava-error-release-version-5-not-supported and follow the steps.

Step 2: Build your Consumer app.

Step 3: Start the Zookeeper as per the directions on this https://kafka.apache.org/quickstart

Step 4: Start the Server as per the directions on this https://kafka.apache.org/quickstart

Step 5: Build the Producer app (if you create a new topic/send a new message). Make sure that the
consumer is reading from the same topic.

Step 6: You can see the message at the console of the IDE that was sent by the producer.
