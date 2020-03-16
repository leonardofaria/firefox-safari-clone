# Firefox Safari Clone

A few days ago I saw one post on [Reddit](https://www.reddit.com/r/FirefoxCSS/comments/fbg0bv/safariesque_for_firefox_73_on_macos/) showing some `userChrome.css` customizations to make Firefox to look like Safari. Decided to get their file and change a couple things. All credits to OP :)

![Screenshot](screenshot.jpg)

## Installation

**Firefox does not support userChrome.css by default. Here are the steps to make it work:**

1. Load **about:config** in the Firefox address bar.
2. Confirm that you will be careful.
3. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` using the search at the top.
4. Toggle the preference by double clicking. True means Firefox supports the CSS files, False that it ignores them.

**Follow these steps to install userChrome.css:**

1. Load **about:support** in the Firefox address bar.
2. Application Basics > Profile Directory > Open Directory
3. Create a folder named `chrome`
4. Paste the `userChrome.css` in this folder

## Editing the file / inspecting the UI

- Go to **about:config**
- Search for `devtools.debugger.remote-enabled` using the search at the top.
- Toggle the preference by double clicking. True means Firefox will enable the option Developer > Browser Toolbox
- Then you can follow this: [How to edit userChrome.css live](https://github.com/adamhotep/Firefox-Tweaks/wiki/How-to-edit-userChrome.css-live)

## Todo

Ideally, I would like to replicate Safari in Sketch or something like that to achieve pixel-perfection but I am not sure when I will do that ¯\\\_(ツ)_/¯

**PRs welcome**

## Credits

- [/u/w19d2e773](https://www.reddit.com/r/FirefoxCSS/comments/fbg0bv/safariesque_for_firefox_73_on_macos/): initial work
- [elementaryos-firefox-theme](https://github.com/Zonnev/elementaryos-firefox-theme): install notes
