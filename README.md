##Project 6
Feed Reader Testing. Test Driven Development with Jasmine

###Overview
This project uses [Jasmine](http://jasmine.github.io/) to test the [google feed reader api](https://developers.google.com/feed/v1/)<br>
Additional libraries and extensions used were [jQuery](http://jquery.com/) and [Jasmine-jquery](https://github.com/velesin/jasmine-jquery)<br>
This project can be viewed at http://projects.jordanyong.com/udacity-jasmine

###Test
- Feeds
	- Ensure all feeds have a non-empty URL
	- Ensure all feeds have a defined name
- Application Menu
	- Ensure that the menu is hidden by default
	- Ensure the menu changes visibility when menu icon is clicked
- Feed Entries
	- Ensures appropriate class assigned in every feed entry
	- Ensure new feed is loaded with change in user request

###References
- [jasmine-jquery](http://www.htmlgoodies.com/beyond/javascript/js-ref/testing-dom-events-using-jquery-and-jasmine-2.0.html)
- [jasmine async](http://www.htmlgoodies.com/beyond/javascript/stips/using-jasmine-2.0s-new-done-function-to-test-asynchronous-processes.html)
- [jasmine documentation](http://jasmine.github.io/2.1/introduction.html)
- [jasmine video tutorial](https://www.youtube.com/playlist?list=PLOxOmO43E6Jt0SruKGxtZs-W3PJN90G_a)