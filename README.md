Fruent Error documents
======================

This is a public repository to give everyone the opportunity to see our error pages, which shouldn't normally be the case.

# Core technologies

* [Yeoman](http://yeoman.io/) - Scaffolding tool for modern web applications.
* [Grunt](http://gruntjs.com/) - JavaScript task runner.
* [Bower](http://bower.io/) - A package manager for the web.

# Getting started

## IntelliJ IDEA 13

* Use File → Import Project
* Select cloned project folder
* Import project from existing sources

## Building the pages

Use grunt to build all error pages.

````bash
grunt
````

## Deploying the pages

````apacheconf
DocumentRoot /opt/apache
ErrorDocument 503 /error-documents/503.html
````
