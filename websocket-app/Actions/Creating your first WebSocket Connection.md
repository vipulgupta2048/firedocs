# Establishing your first WebSocket Connection

In the next few steps, we be creating our very first WebSocket Connection with the Firecamp WebSocket app to monitor events happening in realtime. In this tutorial, we will be using a sample endpoint for establishing and testing our WebSocket Connection.

## Prerequistes
N/A

## Directions
1. Install and open the Firecamp app. If not installed, read the installation instructions.

2. Click `WebSocket` button on the homepage to open the `WebSocket` app

3. In the interface that opens, type the endpoint that you want to test, in the `URL` bar. Firecamp by default has the sample endpoint `ws://echo.websocket.org`.

   - Optionally, you can specify environmental snippets through the dropdown menu and enter protocols needed in the config box located on the left of the `Connect` button.

4. When the endpoint has been configured, click the blue `Connect` button to establish connection.

5. The status of the connection request will appear in the Chatboard. If connecting to the sample endpoint, then the status will be `ws connection established successfully`

6. To close the connection, hover over to the top of the chatboard and click the `Close` button that appears in the bar.

    - In the dialog box, mention the `Close Status` code. It must be `1000` or in between `3000` to `4999`. Optionally, mention the `Reason` as well.
    - When done, click the `Close WS` button.

Voila! You just established your first WebSocket connection successfully and closed it with proper status code and reason. Up next, we will learn how to communicate with the server.


### Short descriptive GIF (w ALT text)


### Additional resources
- Chatboard
- URL bar
- What exactly are WebSocket?
