# How to run this application

Download is available here: https://github.com/LolaGL/feedReaderTesting
Once cloned or donwloaded, open index.html in a browser to run the application.


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!


# Implementations and tests that have been included

1. Tests for `allFeeds` function that loops through each feed in the object and ensures it has a URL defined and that the URL is not empty.
2. Test that ensures the menu element is hidden by default and that its visibility changes when the menu icon is clicked. Menu is displayed at first click and hidden when clicked again.
3. Test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
4. Test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
