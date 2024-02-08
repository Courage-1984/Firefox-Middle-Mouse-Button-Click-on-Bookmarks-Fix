# Firefox-Middle-Mouse-Button-Click-on-Bookmarks-Fix
Firefox Middle Mouse Button Click on Bookmarks Fix to make them actually open behind and also not close the bookmarks menu.

***

To open a bookmarks-folder in the background, hold `Shift`+`middle-click` on the folder, OR hold `Ctrl`+`Shift` and `left-click`.

To open specific bookmarks in the background:

1. Open a new tab
2. Enter `about:config` in the address bar and press enter
3. Look up `browser.tabs.loadBookmarksInBackground` and set it to `true`
4. Look up `browser.bookmarks.openInTabClosesMenu` and set it to `false`
5. Look up `browser.tabs.loadBookmarksInTabs` and set it to `true`
6. Now you can `middle-click` OR hold `Ctrl` while `left-clicking` on your bookmarks!

Voila!

***

SOURCES:

Thanks for this Reddit comment for the solution: [https://www.reddit.com/r/firefox/comments/10c5v35/comment/j4e3wp8/?utm_source=share&utm_medium=web2x&context=3](https://www.reddit.com/r/firefox/comments/10c5v35/comment/j4e3wp8/?utm_source=share&utm_medium=web2x&context=3)

Also: [How to open bookmarks in a new tab (rather than existing window)](https://support.mozilla.org/en-US/questions/1207970)

