# dedguenodgo [![Build Status](https://drone.io/github.com/oadam/dedguenodgo/status.png)](https://drone.io/github.com/oadam/dedguenodgo/latest)

A wishlist website to help my family keep track of Christmas presents.

### Live app on appengine
URL: https://dedguenodgo.appspot.com
login: demo
password: demo

### Javascript only demo
URL: https://rawgit.com/oadam/dedguenodgo/master/src/main/webapp/?demo=1
login: demo
password: demo


# To build
install mvn
run `mvn install`

- if doing java work run the devserver `mvn appengine:devserver`
- if doing javascript work `cd src/main/webapp && python -m SimpleHTTPServer` then go to [http://localhost:8000/index.html?demo=1]()
- to deploy to appengine `mvn appengine:update`
