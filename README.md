#GWT Documentation

* GWT documentation is published under http://www.gwtproject.org/doc/latest/DevGuide.html

##Reference

* Markdown processor: https://github.com/sirthias/pegdown

##Adding content

* See: http://www.gwtproject.org/makinggwtbetter.html#webpage

##Building

* simply run: `mvn clean install`
* after that you will find the generated documentation in `target/generated-site/`.

###Running locally
Run the site locally for easy visual testing

* Run: `mvn install`
* Run: `mvn jetty:run`
* Goto: http://127.0.0.1:8080
