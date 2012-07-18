!SLIDE small

# Client-side JavaScript

	@@@ javascript
	// open a socket
	var socket = new WebSocket('ws://0.0.0.0:8181');

	// respond to events
	socket.onopen = function() {};
	socket.onclose = function() {};
	socket.onerror = function(error) {};
	socket.onmessage = function(message) {};

	// send data and close
	socket.send('hello!');
	socket.close();


!SLIDE

Simple
