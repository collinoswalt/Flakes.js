#Flakes.js

JavaScript for creating snowflakes on your webpage

##Running

simply include these two lines at the bottom of your page:

```HTML
<canvas id="flakes"></canvas>
<script src="flakes.js"></script>
```

If you want this to be responsive to resizing windows, add a window.resize listener:

```javascript
window.onresize = function(){
	document.getElementById("flakes").width 	= window.innerWidth;
	document.getElementById("flakes").height	= window.innerHeight;
}
```

##Requirements
HTML5

##Demo
[Demo can be found here](http://www.collinoswalt.com/list.html)
