```md
# Kilovolt Blog "Lab 10 Functional Programming"

**Author**: Amanda Moen
**Version**: 2.0.1 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
We want to create an administrative page that shows various statistics for the displayed articles and their authors. We also want to implement IIFE's so that all of the function calls are executed upon page load.

## Getting Started
Clone, or fork & clone, npm i, nodemon, then run localhost in the browser.

## Architecture
HTML, CSS3, javascript, jquery, Handlebars, pg, fs, express, highlight.pack.js, marked.js, AJAX, node, SQL, JSON

## Change Log
Article.js TODO's:
07-08-2018 8:05pm - Completed first todo, wrapped article.js in an IIFE.
07-08-2018 8:35pm - Completed second todo, chained together .map() and .reduce() call to get rough count of all words in all articles.
07-08-2018 8:40pm - Completed third todo, chained together .map() and .reduce() call to get an array of unique author names.
07-08-2018 8:50pm - Completed fourth todo, transformed each author string into an object with properties for the author's name and total number of words written by said author from all of their articles.

articleView.js TODO's:
07-08-2018 9:30pm - Completed first todo, wrapped articleView.js in an IIFE.
07-08-2018 9:48pm - Completed second todo, called the Handlebars.compile method.

server.js TODO's:
07-08-2018 7:45pm - Set my conString.

admin.html; index.html; and new.html:
07-08-2018 9:54pm - Completed the Handlebars .compile() method on admin.html
07-08-2018 10:16pm - Completed updating the Article.fetchAll() method for admin.html, and index.html

## Credits and Collaborations
Sarah
```
