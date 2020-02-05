# Establishing your first WebSocket Connection

In the next few steps, we be creating our very first WebSocket Connection with the Firecamp WebSocket app to monitor events happening in realtime. In this tutorial, we will be learning to establish our first WebSocket Connection with Firecamp through a sample endpoint.

## Prerequistes
N/A

## Directions
1. Open the Firecamp app. If not installed, read the installation instructions.

2. Click `WebSocket` button on the homepage to open the `WebSocket` app

3. In the interface that opens, type the endpoint that you want to test in the `URL` bar. Firecamp by default has the sample endpoint `ws://echo.websocket.org` that we will be using to connect.

   - Optionally, you can specify environmental snippets through the dropdown menu and enter protocols needed in the config box located on the left of the `Connect` button.

4. When the endpoint has been configured, click the blue `Connect` button to establish connection with the server.

5. The status `ws connection established successfully` will appear in the Chatboard meaning the server is ready for further communication.

6. Alternatively to close the connection, hover over to the top area of the chatboard and click the blue `Close` button that appears.

    - In the dialog box that appears, mention the `Close Status` code. It must be `1000` or in between `3000` to `4999`. Optionally, mention the `Reason` as well if you are testing it.
    - When done, click the `Close WS` button to close the connection. The connection will be closed listing the `Close Status` and `Reason` in the chatboard.

Voila! You just established your first WebSocket connection successfully and closed it with proper status code and reason. Up next, we will learn how to communicate with the server.


### Short descriptive GIF (w ALT text)


### Additional resources
- Chatboard
- URL bar
- What exactly are WebSocket endpoints?
