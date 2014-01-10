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
    
    // frequent, informal discussions of various things javascript in a beer-enriched environment.
    // 'cause the city's too far, and CalTrain stops running too early.
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
  
    document.write('<marquee>DEAL WITH IT</marquee>');

}

```

