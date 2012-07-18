!SLIDE small

# Server-side JavaScript

	@@@ javascript
	var WebSocketServer = require('ws').Server
	  , wss = new WebSocketServer({port: 8181});

	wss.on('connection', function(ws) {
		ws.on('message', function(message) {});
		ws.on('close', function() {});
		ws.send('something');
	});


!SLIDE

Very similar idea


!SLIDE

# Alternatives to Node


!SLIDE

# Ruby

[EM-WebSocket](https://github.com/igrigorik/em-websocket)

Based on EventMachine


!SLIDE

# Python

[Autobahn|Python](http://autobahn.ws/python)

Based on Twisted


!SLIDE

# Java

[jWebSocket](http://jwebsocket.org/)


!SLIDE

Plenty of choices
