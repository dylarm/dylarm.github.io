---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is Dylan's (Mr. Armitage's) home on the web.
======
***Remove blur from Goalbook***

(only verified to work in Google Chrome, so far)

Right-click (or whatever it is on a Mac) on your bookmarks bar, click "add page," then in the URL box paste the following code:
```javascript
javascript:(function(){var d=document.getElementsByClassName("locked-content");while(d.length>0){d[0].className="accordion-inner linkable medium-text medium-light-text";}})();
```
Name it whatever you want, like Goalbook Unblocker.

Now, when you're on an activity page such as [3-Act Math](https://goalbookapp.com/toolkit/strategy/3-act-math), just clikc the bookmark and it'll remove the text bluring so you can read everything!
