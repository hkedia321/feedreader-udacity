# Feedreader Project
In this project, we have a web-based application that reads RSS feeds. This project focuses on testing. We are using jasmine to write test cases that ensures that everything will work expectedly.

## Running Locally
1. Clone this project: `git clone https://github.com/hkedia321/feedreader-udacity`
2. Open `index.html` in your browser

## Test Cases
- test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty
- test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty
- test that ensures the menu element is hidden by default
- test that ensures the menu changes visibility when the menu icon is clicked
- test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container
- test that ensures when a new feed is loaded by the loadFeed function that the content actually changes

## Resources
- Udacity project code: `https://github.com/udacity/frontend-nanodegree-feedreader`
- Jasmine cheatsheet: `https://devhints.io/jasmine`
- Jasmine documentation: `https://jasmine.github.io/`