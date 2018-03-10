
# Feed Reader Testing

This project is part of **Udacity Front-End Nanodegree**. It is a single page application featuring a set of tests designed to test various aspects of the application.

* [Live project](https://asifchoudhury.github.io/frontend-nanodegree-feedreader/).

#### Test Description
1. Check whether ```allFeeds``` variable has been defined and that it is not empty.
2. Loop through each feed in the ```allFeeds``` object and ensure it has a ```URL``` defined and that the ```URL``` is not empty.
3. Loop through each feed in the ```allFeeds``` object and ensure it has a ```name``` defined and that the ```name``` is not empty.
4. Check to ensure whether the menu element is hidden by default.
5. Check to ensure whether the menu changes visibility when the menu icon is clicked.
6. Check to ensure when the ```loadFeed``` function is called and completes its work, there is at least a single ```.entry``` element within the ```.feed``` container.
7. Check to ensure when a new feed is loaded by the ```loadFeed``` function that the content actually changes.