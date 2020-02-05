# Communicating with the Server

Monitoring events in realtime is what makes WebSockets extremely functional. Hence, in the next few steps, we will be communicating with the server, checking the response and saving messages for future use.

## Prerequisites
- Establishing your First WebSocket connection

We will be using the sample endpoint `ws://echo.websocket.org` to establish the WebSocket connection.

## Directions
1. Open the Firecamp app and click the `WebSocket` option on the homepage.

2. Type the endpoint `ws://echo.websocket.org` in the URL bar if not there already and click the blue `Connect` button. The status on the chatboard will be `ws connection established successfully` meaning the connection has been established and we can start communicating with the server.

3. Type a message in `Text` or `JSON` format in the Message panel at the bottom of the WebSocket app.

4. Click the `Send` button to send the message to the server. The response from the server can be checked in the Chatboard. This specific endpoint returns the same message the user writes in response.

5. Try typing more messages and checking the response from the server in realtime on the Chatboard.

6. To save a message, click the `Send & Save` button next to the `Send` button. Optionally, you can save a group of messages together by mentioning a Title in the `Title` bar. The messages are saved in the `Messages` panel on the right for later use.

Voila! You successfully connected and communicated with the server. Up next, we will learn how to manage and send Saved Messages.


### Short descriptive GIF (w ALT text)


### Additional resources
- Chatboard
- URL bar
- Message panel
- Saved Messages
