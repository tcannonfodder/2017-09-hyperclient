# 2017-09 Hypermedia Client Tutorial

Content for hypermedia client tutorial for 2017-09 RESTFest Greenville

## Tutorial Day
This tutorial is set up for a 1/2 day. The aim is to get an idea of what it takes to design and code a simple  hypermedia client. There is a lot of code in this tutorial. It is possible we won't get through all of it in this one session but I included both starter templates and completed editions of each of the major coding sessions. That way you can review this after the tutorial on your own.

### Agenda

 - 13:00 - 13:15 : What is a Hypermedia client? (slides)
 - 13:15 - 13:30 : Initializing the SPA Client
 - 13:30 - 14:00 : Enabling `title` and `content` elements
 - 14:00 - 14:30 : Enabling `links` elements 
 - 14:30 - 15:30 : Enabling `items` elements 
 - 15:30 - 16:00 : Enabling `queries` elements 
 - 16:00 - 16:30 : Enabling `templates` elements

## Prep for the Tutorial
In order to code and run the examples, you'll need the following:

 . Laptop that can run NodeJS
 . The starter files from this repo (clone the repo or download the ZIP)
 
## Background
Below are some background comments on the reasons this hypermedia example looks the way it does.

 * The Single-Page App
 * The `dom-help.js` Library
 * Semantic UI for CSS Support
 
### The Single-Page App
This client example uses a [Single-Page App](https://en.wikipedia.org/wiki/Single-page_application) (SPA) implementation pattern. In some ways this is a bit of a bummer since many SPA-style apps 'break' basic browser functionality (e.g. the back button). However, for our sample example, the SPA makes it easy to build everything in one place and see it all working together. I've also left out some additional code that would make the SPA more 'browser-friendly' since that code kind of gets in the way of our exercise today.

In production, you might want to use a more robust SPA framework or not use an SPA pattern at all. That's no problem. 

### The `dom-help.js` Library
The hypermedia client example we'll work on relies on the `dom-help.js` custom library. This library contains short-hand methods for things like HTML DOM manipulation and FORM handling. The library is quite small but reduces the amount of typing needed to generate solid client code.  At the start, it may be a bit difficult to learn the library's functions and arguments but hopefully, but the end of the session, you'll get the hang of it.

In production cases, you'd probably replace `dom-help.js` with JQuery or some other more robust library. I used this simple one to keep the footprint of the app small and reduce the learning curve for a helper lib.

### Semantic UI for CSS Support
The example relies on the [Semantic UI](http://semantic-ui.com/) project for layout and styling. This is a very lightweight library and is also prety unobtrusive. The SPA Container HTML for this example has a handful of `DIV` elements in order to support Semantic CSS layout but there is almost no other 'cruft' HTML needed.

In a production app, you might want to use a CSS library like LESS or some other common framework. Lucky for us, we won't need to interact much with the styling and things will have a good look-and-feel anyway.
 






