# Readme

2/17: -Going to add simulcast

I'm going to come back to this and make a basic but attractive UI, as well as make it as easy to deploy as possible and write up a basic walkthrough for doing so here in the README.

To include in this readme:

-Note about WS heartbeat

-Note about TLS and deployment... (include files in this repo?)

-Walkthrough for nginx, certbot, systemd

For this project I have modified and extended server and client code from the Pion examples repository directory called sfu-ws: https://github.com/pion/example-webrtc-applications/tree/master/sfu-ws
Changes have been made to facilitate TLS, www hosting, add support for 'rooms', close connections (both RTCPeerConnection and WebSocket) in the client under different circumstances, and add additional error handling to the server.
