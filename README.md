beerjspaloalto
============

```js

switch (desire) {

  case 'next':
    
    var nextMeetup = checkIssues();
    if (!nextMeetup) {
      file(new Issue());
    }
    break;
    
  case 'info':
    
    // Support for people who love javascript and those who love them,
    // in the heart of Silicon Valley. Because the city's too far, and
    // CalTrain stops running too early.
    var beer = require('beer');
    var js = require('javascript');
    var event = new Meetup({
      geo: 'Palo Alto, CA',
      location: 'Rose and Crown Pub'
    });
    event.mixin(beer, js);
    event.mixin(require('more beer'));
    throw event;
    
  case 'meetup':
    
    window.location = 'http://www.meetup.com/beer-js-palo-alto/';
    
  case 'contact':
  
    return {
      'commissioner': 'mailto:beerjs@potch.me',
      'twitter': '@beerjspaloalto'
    };
  
  default:
  
    document.write('<MARQUEE><BLINK>DEAL WITH IT</BLINK></MARQUEE>');

}

```

