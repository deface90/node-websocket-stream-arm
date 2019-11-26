# Node Websocket Stream container (arm64v8)

Simple docker container to stream input data (e.g. video stream from ffmpeg) to websocket clients.

Using:

``` docker run -d deface90/node-websocket-stream-arm ```

Container will wait for input stream into endpoint:
```http://127.0.0.1:8081/stream-input```

WebSocket clients should connect to:
``` ws://'+document.location.hostname+':8082/```