#swipe.js 
A simple script to add swipe events to a web page

##Usage

    function onLeft() {
    	// Do something when the user swiped left
    }
    
    ...
    
    var target = document.getElementById("myElt");
    
    sw = new Swipe(target,onLeft,onRight,onUp,onDown);

##Demo

[Try out the demo](http://kaizouman.github.com/swipe/) on a touch-enabled device.

##License

You may use this code under the terms of the MIT license.