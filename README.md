# Readme

## Todos

- Add simulcast
- Work on congestion control
- Create presentable UI

## Readme Todos

To include in this readme:

-Note about WS heartbeat

-Note about TLS and deployment... (include files in this repo?)

-Walkthrough for nginx, certbot, systemd

For this project I have modified and extended server and client code from the Pion examples repository directory called sfu-ws: https://github.com/pion/example-webrtc-applications/tree/master/sfu-ws
Changes have been made to facilitate TLS, www hosting, add support for 'rooms', close connections (both RTCPeerConnection and WebSocket) in the client under different circumstances, and add additional error handling to the server.
