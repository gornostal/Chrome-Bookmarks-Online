Chrome Bookmarks Online
=======================


This project allows you to have an online copy of your Google Chrome bookmarks.
You just need a regular Dropbox account for accessing bookmarks page through a [Dropbox](https://www.dropbox.com/) public folder.

Installation
------------
* [Download](https://github.com/gornostal/Chrome-Bookmarks-Online/zipball/master) or clone the project.
* Under the Dropbox public folder create a `bookmarks` folder and put these files in there
* Create in your OS new task in a task scheduler for copying `Bookmarks` file to the Dropbox folder. For Windows users this file is located in `C:\Users\<Username>\AppData\Local\Google\Chrome\User Data\Default\Bookmarks`, for Linux users — `/home/<Username>/.config/google-chrome/Default/Bookmarks` (don't make symbolic links for Dropbox, because it not syncing them properly)
* Access your bookmarks from URL: `http://dl.dropbox.com/u/<DopboxID>/bookmarks/index.html`

Configuration
-------------

You can enable (or disable) favicons by setting `loadFavicons` to `true` (or `false`) in file `index.html` at `line 15`. Without favicons page loads much faster.


P.S.
----

Will be glad to get any advice on how to improve the project. 