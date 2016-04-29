------------
Highlight.js
------------
A code syntax highlighting framework written in Javascript.

Note: Highlight.js is not designed to work out of the box from GitHub, it must be built first. Do this for all available languages by navigating to the project directory in the console and entering:
	node tools/build.js -t node
Or for common languages:
	node tools/build.js :common

--------
Showdown
--------
A markdown to HTML text converter written in Javascript that converts
markdown text in-browser.

Note: When created a Showdown Converter object, must load the 'codehighlight' extension.
var converter = new showdown.Converter({extensions: ['codehighlight']});

----------------------
Showdown-CodeHighlight
----------------------
An extension for Showdown that enables use of Highlight.js for code highlighting within the converted markdown.