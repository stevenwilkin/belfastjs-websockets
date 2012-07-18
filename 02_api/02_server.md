!SLIDE smaller

# Server API

	@@@ javascript
	var WebSocketServer = require('ws').Server
	  , wss = new WebSocketServer({port: 8181});

	wss.on('connection', function(ws) {
		ws.on('message', function(message) {});
		ws.on('close', function() {});
		ws.send('something');
	});
