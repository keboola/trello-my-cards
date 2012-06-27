# My Cards For Trello - Chrome Extension

This extension provides you quick access to all your cards in [Trello collaboration tool](https://trello.com/).
Cards are grouped by boards and sorted by last activity in card.

Several types of cards are displayed:

  * cards assigned to me
  * cards commented by me
  * cards where I am mentioned

This extension was inspired by [Trello Cards extension](https://chrome.google.com/webstore/detail/ofhppploglffgmbgmidejclkaipbjpac?hl=cs),
extended by card types, filtering, search, sorting, due dates.

# Warning

The extension is on a very early stage of development, so expect some hiccups.

# Installation

[Install from Chrome Web Store](https://chrome.google.com/webstore/detail/gfibakafolondafoldolofciodfnbado)

Installation from source files:

  * Download and unpack this repository to local file system
  * Copy file key.template.js to key.js
  * Go to https://trello.com/1/appKey/generate and copy created app key
  * Open file key.js in text editor and replace phrase "INSERT_YOUR_APP_KEY_HERE" with copied app key
  * Compile coffescript into javascript. Run cake compile from projesct folder.
  * Continue here: http://code.google.com/chrome/extensions/getstarted.html#load