Draw a Blank
============
Simple Chrom{e,ium} extension that replaces the default New Tab page with a blank one

What?
-----
If you've looked through Chrome's preferences, you might have noticed that there's no option to
change what page is loaded when you open a new tab: a setting that users of other browsers might
take for granted.

_Draw a Blank_ does one thing and one thing only: it overrides Chrome's default New Tab page with
an entirely blank one.

Installation
------------
Installing is easy:

1. Clone this repository to your machine.
2. Open the "Extensions" settings in Chrome.
3. Check the "Developer mode" checkbox in the upper right corner.
4. Click "Load unpacked extension..." and choose the directory into which you cloned this extension.
5. _Done!_

Odds & Ends
-----------

* **Why build [another][others] extension for this?**

  If all you want is for Chrome to open new tabs to a blank page, you shouldn't have to download
  a sketchy extension and worry about its permissions. _Draw a Blank_ is open source and needs
  declare no special permissions at all. Google has made it [trivial][google] to override pages,
  and that's all _Draw a Blank_ does.

* **Why are there no icons?**

  I want the blank tab page to be extremely minimal, yet I do not want it to detract from the
  otherwise clean Chrome experience. Chrome's default New Tab page has no favicon at all.
  Unfortunately, we can't exactly replicate that since Chrome _does_ load an actual page as part
  of the override. And when an icon is provided ([16x16][icons] or otherwise), it gets used as
  the favicon. I could provide an alternative default favicon, but I'd rather not. And I don't
  want to include the one used in Chrome itself so that I can avoid any legal bumps.

* **Why isn't this in the [Web Store][store]?**
  
  I just haven't put it there.

* **What's in the actual "blank" page?**
  
  Not much! But it _is_ valid HTML5. You can [check it][valid] yourself!

License
-------
_Draw a Blank_ is released under the [MIT][mit] license. Nothing special here.

DISCLAIMER
----------
I give no assurance of this utility's security, and I do not guarantee that it will not zap your
computer and fry your homedir. _Use at your own risk._

Bugs
----
This is a "works-for-me-maybe" project: I do not guarantee that any bugfixing will occur.

[others]: https://chrome.google.com/webstore/search-extensions/blank%20new%20tab
[google]: http://developer.chrome.com/extensions/override.html
[icons]:  http://developer.chrome.com/extensions/manifest.html#icons
[store]:  https://chrome.google.com/webstore
[valid]:  http://validator.w3.org
[mit]:    http://www.tldrlegal.com/l/MIT
