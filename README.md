AngularJS [![Build Status](https://travis-ci.org/angular/angular.js.svg?branch=master)](https://travis-ci.org/angular/angular.js)
=========

AngularJS lets you write client-side web applications as if you had a smarter browser.  It lets you
use good old HTML (or HAML, Jade and friends!) as your template language and lets you extend HTML’s
syntax to express your application’s components clearly and succinctly.  It automatically
synchronizes data from your UI (view) with your JavaScript objects (model) through 2-way data
binding. To help you structure your application better and make it easy to test, AngularJS teaches
the browser how to do dependency injection and inversion of control.

Oh yeah and it helps with server-side communication, taming async callbacks with promises and 
deferreds. It also makes client-side navigation and deeplinking with hashbang urls or HTML5 pushState a
piece of cake. Best of all?? It makes development fun!

* Web site: http://angularjs.org
* Tutorial: http://docs.angularjs.org/tutorial
* API Docs: http://docs.angularjs.org/api
* Developer Guide: http://docs.angularjs.org/guide
* Contribution guidelines: [CONTRIBUTING.md](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md)
* Dashboard: http://dashboard.angularjs.org

Building AngularJS
---------
[Once you have your environment set up](http://docs.angularjs.org/misc/contribute) just run:

    grunt package


Running Tests
-------------
To execute all unit tests, use:

    grunt test:unit

To execute end-to-end (e2e) tests, use:

    grunt package
    grunt test:e2e

To learn more about the grunt tasks, run `grunt --help` and also read our
[contribution guidelines](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md).


[![Analytics](https://ga-beacon.appspot.com/UA-8594346-11/angular.js/README.md?pixel)](https://github.com/igrigorik/ga-beacon)

Introduction for Non-Developers
---------
 
AngularJS is an open-source JavaScript framework that lets you develop client-side web applications using the amicable HTML as your template language. HTML is great for structuring static web page but falters when it is used for building dynamic web content. To address this issue, AngularJS adapts and extends on the traditional HTML syntax, lets you attach behavior to an otherwise static element through framework built-in or _AngularJS flavored new HTML tag or tag attributes_, called AngularJS Directives, that can be embedded in the HTML page. Some very powerful AngularJS Directives come built-in and many more can be invented by the application developer. This is one of the way AngularJS gives the power in the hands of programmers using it.
 
The most notable feature of the framework is its two-way data binding, which means changes in the Model (data, your JavaScript object) automatically propagate to the View (the user interface), likewise, any alteration to the View is reflected in the Model. This automatic synchronization of Models and Views circumvents the need to constantly manipulate DOM and relieves the backend server of changing and updating any of them manually, leading to improved testability and a more responsive/fluid web experience.
 
AngularJS implements dependency injection to declaratively describe how your software components should be connected, this approach brings traditionally server-side actions to the front-end web application, consequently, much of the burden on the server can be reduced.
 
The goal of AngularJS is to relieve you from worrying about DOM manipulation, and to decouple the client side of an application from the server side to make it possible for development work to progress in parallel, the framework also provides structure for the entire journey of building a web application: from creating the UI, through writing the underlying model and testing.
