/*
1) Run Growtopia
2) Open console (F12)
3) Insert code & run
*/


var event = new KeyboardEvent('keydown', {
	key: 'space',
	ctrlKey: true
});

setInterval(function(){
	for (i = 0; i < 100; i++) {
		document.dispatchEvent(event);
	}
}, 0);
