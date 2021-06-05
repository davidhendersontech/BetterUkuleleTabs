# BetterUkuleleTabs
Make ukulele-tabs.com awesome!

Hate not being able to read long tabs on a desktop without scrolling horizontally?    
No longer! BetterUkuTabs solves all.

## Install
1. Simply install the greasemonkey addon in your favorite browser.
2. Click the monkey, click new user script.
3. Copy the following into the new script that just opened
```
// ==UserScript==
// @name     BetterUkeTabs
// @version  1
// @grant    none
// @match 	 https://www.ukulele-tabs.com/uke-songs/*/*
// @run-at 	 document-idle
// ==/UserScript==

const sidebar = document.querySelector("#sidebar")
sidebar.hidden = true

const main = document.querySelector("#main")
main.className = "medium-20"
// lol
const scrollMe = document.querySelector("#ScrollMe")
scrollMe.hidden = true
scrollMe.className = ""
```
5. Go to your favorite ukulele tabs and watch the magic happen


### Notes and Contact
Why Ukulele-tabs.com? It was so simple..


Test it out! [David's Favorite Tab](https://www.ukulele-tabs.com/uke-songs/jake-shimabukuro/bohemian-rhapsody-uke-tab-34114.html)
Built with love by [Rj](https://github.com/rjheim) and [David](https://github.com/notDavidHenderson)


