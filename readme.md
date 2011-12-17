#Ledpong

A Node library to interact with Tetalab ledpong using arduino firmata protocol.

#Usage

    var ledpong = require('ledpong');
    var board = new ledpong.Board('path to usb',function(){
      //arduino is ready to communicate
    }); 

#REPL

If you run *ledpong* from the command line it will prompt you for the usb port.  Then it will present you with a REPL with a board variable available.
