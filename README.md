node-nzbget
================
Node interface for [NzbGet](http://nzbget.net).

Work In Progress.

Usage example
================
```javascript
var nzbget = require('node-nzbget');

var ng = new nzbget({
	url: '<host:port>', 
	username: '<username>',
	password: '<password>',
});

ng.version().then(function(res) {
	// data in res
});

ng.status().then(function(res) {
	// data in res
});

ng.servervolumes().then(function(res) {
	// data in res
}); 

ng.history().then(function(res) {
	// data in res
});

ng.listgroups().then(function(res) {
	// data in res
});

ng.listfiles().then(function(res) {
	// data in res
});
```
