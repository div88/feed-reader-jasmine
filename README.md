# Feed Reeder Test Project

A web-based application that reads RSS feeds is given in this project. Using jasmine, tests are written to ensure that the application works as per the requirements.

## Table of Contents


* [Instructions to test](#instructionsToTest)
* [Instructions](#instructions)
* [Contributing](#contributing)
* [Dependencies](#dependencies)

## Instructions to test

Clone or download the game [here](https://github.com/div88/feed-reader-jasmine.git)
Open index.html in your favorite browser
Test is run and all the results are shown at the bottom of the page once the page is loaded


## Tests written

- A test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
 - A test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
- A new test suite named "The menu".
- A test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
- A test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
- A test suite named "Initial Entries".
- A test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
- A test suite named "New Feed Selection".
- A test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.

## Contributing

The starter code was provided by Udacity and was cloned from [git repo](https://github.com/udacity/frontend-nanodegree-feedreader)

## Dependencies

Jasmine
The Roboto font
