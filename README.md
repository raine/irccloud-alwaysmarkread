irccloud.AlwaysMarkRead.user.js
===============================

The default behavior of [IRCCloud.com](http://www.irccloud.com) is such that
each channel has to be manually marked as read if the unread backlog exceeds
what is currently visible in the window. This userscript addresses the
problem by always marking a buffer read once activated, similarly to how
Irssi behaves.

See also: [irccloud.BufSwitch](https://github.com/raneksi/irccloud-bufswitch).

# Installation

I have tested the userscript on Chrome and Firefox using Greasemonkey.

## Firefox

1. Install [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/).
2. Go to http://userscripts.org/scripts/source/177728.user.js and click **Install**.

## Chrome

### Method 1 (Recommended)

This method provides automatic updates for the script.

1. Install [Tampermonkey extension](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) on Chrome Web Store.
2. Go to http://userscripts.org/scripts/source/177728.user.js and click
   **OK** to confirm installation.

### Method 2

1. Download [`irccloud.AlwaysMarkRead.user.js`](https://raw.githubusercontent.com/raine/irccloud-alwaysmarkread/master/irccloud.AlwaysMarkRead.user.js) to your computer.
2. Go to the **Extensions** view in Chrome ([`chrome://extensions`](chrome://extensions)).
3. Drag the `irccloud.AlwaysMarkRead.user.js` file on the **Extensions** page. It
   should say "Drop to install" as you do so.
