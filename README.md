# Feed Reader Testing Project 

This project was built for the Udactity Front-End Nanodegree Program.


# Table of Contents

* [About the Project](#about-the-project)
* [Resources](#resources)


# About the Project

This project is a web-based application that reads RSS feeds. it includes Jasmine API (Behavior-Driven JavaScript) that's used to test code behavior and validate that application runs perfectly.


## Steps to run the project:

* open index.html in your browser.
* The tests were written in the jasmine/spec/feedreader.js file.
* The test results appears at the bottom of the index.html page.
* Passed tests are colored with green, and failed tests are colored with red.


## Jasmine tests included in the project:
you can find all tests in jasmine/spec/feedreader.js.

* The first suite named (RSS Feeds) includes the following tests:
1.  a test to make sure that the allFeeds variable has been defined and not empty.
2. a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
3. a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.

* The second suite named (The menu) includes the following tests:
1. a test that ensures the menu element is hidden by default. 
2. a test that ensures the menu display when clicked and does it hide when clicked again.

* The third suite named (Initial Entries) includes the following tests:
1. a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.

* The third suite named (New Feed Selection) includes the following tests:
1. a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.


# Resources
### Jasmine Documentation
* https://jasmine.github.io/pages/docs_home.html

### Youtube Tutorial about Jasmine
* https://www.youtube.com/watch?v=dFz2h7o0vqs

### Testing Your JavaScript With Jasmine
* https://code.tutsplus.com/tutorials/testing-your-javascript-with-jasmine--net-21229


