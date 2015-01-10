speedometer
===========

Smooth speedometer written by [TypeScript](http://www.typescriptlang.org/).

usage
===========

    
    var sm = new SpeedoMeter();
    
    sm.addListener({
        onReport:function(pos, speed){}
    });
    
    sm.start();
    
    sm.push(2e5);


author
===========

 - <yanni4night@gmail.com>

license
===========
MIT