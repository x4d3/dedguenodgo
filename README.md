dedguenodgo
===========

A wishlist website to help my family keep track of Christmas presents.

The live app is available on [google app engine](https://dedguenodgo.appspot.com) with login demo/demo. You can also test the [localstorage based demo](http://oadam.github.com/dedguenodgo/index.html?demo=1) hosted on github.

[![Build Status](https://drone.io/github.com/oadam/dedguenodgo/status.png)](https://drone.io/github.com/oadam/dedguenodgo/latest)

To build
--------
install mvn
run `mvn install`

- if doing java work run the devserver `mvn appengine:devserver`
- if doing javascript work `cd src/main/webapp && python -m SimpleHTTPServer` then go to [http://localhost:8000/index.html?demo=1]()
- to deploy to appengine `mvn appengine:update`
