Chrome Bookmarks Online
=======================


This project allows you to have an online copy of your Google Chrome bookmarks.
You just need a regular Dropbox account for accessing bookmarks page through a [Dropbox](https://www.dropbox.com/) public folder.

Installation
------------
* [Download](https://github.com/gornostal/Chrome-Bookmarks-Online/zipball/master) or clone the project.
* Under the Dropbox public folder create a `bookmarks` folder and put these files in there
* Open that folder and make a symlink to `/home/<Username>/.config/google-chrome/Default/Bookmarks`. If you are on Windows, create new task in task scheduler for copying `Bookmarks` file to the Dropbox folder. File located in `C:\Users\<Username>\AppData\Local\Google\Chrome\User Data\Default\Bookmarks`.
* Access your bookmarsk from URL: `http://dl.dropbox.com/u/<DopboxID>/bookmarks/index.html`

Configuration
-------------

You can enable (or disable) favicons by setting `loadFavicons` to `true` (or `false`) in file `index.html` at `line 15`. Without favicons page loads much faster.


P.S.
----

Will be glad to get any advice on how to improve the project. 