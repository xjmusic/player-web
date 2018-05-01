# California!™

https://california.outright.io/

### ECMAScript 6

Overview:

    class Point {
        constructor(x, y) {
            this.x = x;
            this.y = y;
        }
        toString() {
            return '(' + this.x + ', ' + this.y + ')';
        }
    }
    
    class ColorPoint extends Point {
        constructor(x, y, color) {
            super(x, y);
            this.color = color;
        }
        toString() {
            return super.toString() + ' in ' + this.color;
        }
    }
    
    let cp = new ColorPoint(25, 8, 'green');
    cp.toString(); // '(25, 8) in green'
    
    console.log(cp instanceof ColorPoint); // true
    console.log(cp instanceof Point); // true
    
See also: http://2ality.com/2015/02/es6-classes-final.html

### Source Code Repository

http://code.outright.io/game/california-web

Copyright (c) 2018, Outright Mental Inc. (https://outrightmental.com) All Rights Reserved.

