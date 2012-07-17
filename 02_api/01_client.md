!SLIDE smaller

# Client API

	@@@ javascript
	var socket = new WebSocket('ws://0.0.0.0:8181');

	socket.onopen = function() {};
	socket.onclose = function() {};
	socket.onerror = function(error) {};
	socket.onmessage = function(message) {};

	socket.send('hello!');
	socket.close();
