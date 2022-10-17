# How to restore Firefox UI to have classic look
1. In `about:config`, make sure `toolkit.legacyUserProfileCustomizations.stylesheets` is set to `true`.
2. Type `about:support` in browser and look for `Profile Folder`. Open the folder.
3. In the opened window, look for the `chrome` folder. Create one if it does not exist (or just copy the folder from this git repo).
4. Add `userChrome.css` file to that folder.

Credits are located in `userChrome.css`. Style is current as of Firefox v103.

**Note:** If the UI still looks weird, the style may have changed in the latest Firefox version. Check the links in the `userChrome.css` to see if there is an update.