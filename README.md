# shout-into-the-ether

Delayed Message Delivery via Text and Email

## Description:
A simple program that allows users to send messages via text and/or email to their specified recipients. However, unlike traditional messaging apps, all pending message deliveries are queued for an arbitrary, random amount of time, ranging from hours to years. 

The simple caveat is, that, much like Costar's "Chaos Mode," all pending message deliveries are queued for an arbitrary, random amount of time. Messages may take between hours and years to actually deliver. Call it fate, call it karma. Call it astrology, call it a RNG. Idk.

This adds an element of surprise and unpredictability to message delivery, reminiscent of Chaos Mode in Costar. The project is accessible as a web app and also supports your favorite command-line interface (CLI), boasting a clean and minimalistic UI.


## Key Features:
1. Message Queueing: Implement a message queue system that randomly delays the delivery of pending messages within a specified range of time.
2. Text and Email Integration: Enable users to send messages through both text (SMS) and email mediums for flexibility.
3. Recipient Specification: Allow users to specify the recipient(s) and customize the content of the messages.
4. Web App and CLI Support: Provide users with the option to interact with the program through a web app or their preferred command-line interface.
5. Clean UI: Design a minimalistic and user-friendly interface to create and manage messages.
6. Random Number Generator (RNG): Utilize an RNG to determine the arbitrary time delay for each message delivery.


## Best Coding Languages:
Python is an ideal language for this project due to its versatility, ease of integration with web frameworks, and support for CLI applications. For web app development, you can use Python web frameworks like Flask or Django.


## Basic Workflow:
1. User Input: Prompt users to specify the recipient(s) and compose the message content.
2. Message Queue: Place the message in a queue, and use an RNG to determine the random delivery time within the predefined range.
3. Delivery Mechanism: Implement mechanisms to send messages via text (using SMS API) and email (using email sending libraries).
4. Web App and CLI Support: Develop a web-based interface for users to create and manage messages. Additionally, create a CLI interface for users who prefer command-line interactions.
5. Clean UI: Design a simple and intuitive user interface for a seamless user experience.
6. Testing: Thoroughly test the message queue system to ensure proper randomization and delivery.


## Basic I/O Details:
The web app will require user interaction through a web browser. Users can access the application, input message details, and specify recipients. For the CLI, users can run the shout-into-the-ether program, enter the message content and recipient(s), and await the random message delivery.

shout-into-the-ether adds a fun and whimsical twist to traditional messaging, offering an intriguing and exciting way to communicate with friends, family, or even future versions of yourself. The project aims to engage users with its unpredictability and mysterious delivery times while maintaining a clean and user-friendly interface.
