# ChatKafka

Chat Application using Kafka
This is a simple chat application written in Java that utilizes Apache Kafka for message handling. The application features a basic GUI created using SwingUIDesigner.

Features
User Message Persistence:

Users can see messages from the moment they log in, implemented using offsets on specific partitions.

Basic Login System:

Credentials are stored and verified in memory.

Error Handling:

Specific error handling, such as incorrect login attempts, is implemented.

Chat Management:
-Users can create new chats.

-Users can add other users to a chat.

-Users can remove other users from a chat.

-Only the chat creator can ban/unban users from a chat.
