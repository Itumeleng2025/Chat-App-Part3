# Chat-App-Part3
Part 3: Store Data and Display Task Report

This part adds data storage, arrays, and reports to the app. It also adds automated unit tests using JUnit 4.

Features

The app stores messages in the following arrays.
• Sent Messages
• Disregarded Messages
• Stored Messages
• Message Hashes
• Message IDs

The app loads stored messages from the JSON file into an array.

Users can perform the following tasks.
• View sender and recipient details for each sent message.
• View the longest message.
• Search for a message using the message ID.
• Search for messages sent or stored for a specific recipient.
• Delete a message using the message hash.
• View a full report that lists the message hash, recipient, and message text.

Unit Tests

The project includes automated JUnit 4 tests.
The tests use the required test data and verify the expected results.

Tests included
• Sent messages array is correctly populated.
• The longest message is correctly identified.
• Searching by message ID returns the correct message.
• Searching by recipient returns the correct messages.
• Deleting a message by hash works.
• The report displays all sent messages with the required details.

Test Data Used
Message 1
Recipient: +27834557896
Message: Did you get the cake
Flag: Sent

Message 2
Recipient: +27838884567
Message: Where are you? You are late! I have asked you to be on time.
Flag: Stored

Message 3
Recipient: +27834484567
Message: Yohoooo, I am at your gate.
Flag: Disregard

Message 4
Recipient: 0838884567
Message: It is dinner time
Flag: Sent

Message 5
Recipient: +27838884567
Message: Ok, I am leaving
