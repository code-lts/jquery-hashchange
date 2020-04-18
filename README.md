# jQuery hashchange event #
[http://benalman.com/projects/jquery-hashchange-plugin/](http://benalman.com/projects/jquery-hashchange-plugin/)

Version: 2.0, Last updated: 4/18/2020

This jQuery plugin enables very basic bookmarkable #hash history via a cross-browser window.onhashchange event.

Visit the [project page](http://benalman.com/projects/jquery-hashchange-plugin/) for more information and usage examples!


## Documentation ##
[http://benalman.com/code/projects/jquery-hashchange/docs/](http://benalman.com/code/projects/jquery-hashchange/docs/)


## Examples ##
These working examples, complete with fully commented code, illustrate a few
ways in which this plugin can be used.

[http://benalman.com/code/projects/jquery-hashchange/examples/hashchange/](http://benalman.com/code/projects/jquery-hashchange/examples/hashchange/)
[http://benalman.com/code/projects/jquery-hashchange/examples/document_domain/](http://benalman.com/code/projects/jquery-hashchange/examples/document_domain/)

## Support and Testing ##
Information about what version or versions of jQuery this plugin has been
tested with, what browsers it has been tested in, and where the unit tests
reside (so you can test it yourself).

### jQuery Versions ###
1.2.6, 1.3.2, 1.4.1, 1.4.2

### Browsers Tested ###
Internet Explorer 6-8, Firefox 2-4, Chrome 5-6, Safari 3.2-5, Opera 9.6-10.60, iPhone 3.1, Android 1.6-2.2, BlackBerry 4.6-5.

### Unit Tests ###
[http://benalman.com/code/projects/jquery-hashchange/unit/](http://benalman.com/code/projects/jquery-hashchange/unit/)


## A more robust solution ##

This plugin is, by design, very basic. If you want to add lot of extra utility around getting and setting the hash as a state, and parsing and merging fragment params, check out the [jQuery BBQ](http://benalman.com/projects/jquery-bbq-plugin/) plugin. It includes this plugin at its core, plus a whole lot more, and has thorough documentation and examples as well. You can't have too much of a good thing!


## Known issues ##

While this jQuery hashchange event implementation is quite stable and robust, there are a few unfortunate browser bugs surrounding expected hashchange event-based behaviors, independent of any JavaScript window.onhashchange abstraction. See the following examples for more information:

Chrome: Back Button
[http://benalman.com/code/projects/jquery-hashchange/examples/bug-chrome-back-button/](http://benalman.com/code/projects/jquery-hashchange/examples/bug-chrome-back-button/)

Firefox: Remote XMLHttpRequest
[http://benalman.com/code/projects/jquery-hashchange/examples/bug-firefox-remote-xhr/](http://benalman.com/code/projects/jquery-hashchange/examples/bug-firefox-remote-xhr/)

WebKit: Back Button in an Iframe
[http://benalman.com/code/projects/jquery-hashchange/examples/bug-webkit-hash-iframe/](http://benalman.com/code/projects/jquery-hashchange/examples/bug-webkit-hash-iframe/)

Safari: Back Button from a different domain
[http://benalman.com/code/projects/jquery-hashchange/examples/bug-safari-back-from-diff-domain/](http://benalman.com/code/projects/jquery-hashchange/examples/bug-safari-back-from-diff-domain/)

Also note that should a browser natively support the window.onhashchange
event, but not report that it does, the fallback polling loop will be used.


## Release History ##

[CHANGELOG.md](CHANGELOG.md)


## License ##
Copyright (c) 2010 "Cowboy" Ben Alman
Dual licensed under the MIT and GPL licenses.
[http://benalman.com/about/license/](http://benalman.com/about/license/)
