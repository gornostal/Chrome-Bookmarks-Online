Chrome Bookmarks Online
=======================


This project allows you to have an online copy of your Google Chrome bookmarks.
You just need a regular Dropbox account for accessing bookmarks page through a Dropbox public folder.

Installation
------------

* Under the Dropbox public folder create a `bookmarks` folder and put these files in there
* Create in your OS new task in task scheduler for copying `Bookmarks` file to the Dropbox folder. 
For Windows users this file located in `C:\Users\<Username>\AppData\Local\Google\Chrome\User Data\Default\Bookmarks`, for Linux users — `/home/<Username>/.config/google-chrome/Default/Bookmarks`
* Access your bookmarsk from URL: `http://dl.dropbox.com/u/<DopboxID>/bookmarks/index.html`

Configuration
-------------

You can enable (or disable) favicons by setting `loadFavicons` to `true` (or `false`) in file `index.html` at `line 15`.


P.S.
----

Will be glad to get any advice on how to improve the project. 