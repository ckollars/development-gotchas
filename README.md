# development-gotchas
A list of links that are solutions to some pesky development bugs and issues

##### Problem: Position fixed doesn't get painted in iOS until after the scroll finishes. 

##### Fix: Add `transform: translate3d(0,0,0);` or `transform: translateZ(0);` to the element that gets `position: fixed` added. [Source](http://stackoverflow.com/questions/32875046/ios-9-safari-changing-an-element-to-fixed-position-while-scrolling-wont-paint)
