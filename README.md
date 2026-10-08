# Feed Block privacy policy

_Last updated: October 8, 2026_

Feed Block is a Chrome extension that hides endless feeds on YouTube, Facebook, TikTok, Instagram, X (Twitter), Reddit, LinkedIn, Pinterest, Snapchat, and Threads.

## What it collects

**Nothing.** Feed Block does not collect, send, sell, or share any personal data. It has no analytics, no tracking, no ads, and no server.

## What it stores, and where

| Data | Where | Why |
| --- | --- | --- |
| Your settings (which switches are on, allowed Facebook groups, allowed subreddits, your shortcut key) | `chrome.storage.sync`, inside Chrome | So your settings follow you to other computers signed in to the same Chrome profile. Google handles this sync; Feed Block never sees it. |
| Names and pictures of the Facebook groups you allowed, and any names you gave them | `chrome.storage.local`, inside Chrome (this computer only) | So the popup and Facebook page show "Bike Swap Chicago" instead of a number. Read from the Facebook pages you already have open; never sent anywhere. |
| The address of your last search results page on each site | `chrome.storage.session` and the tab's session storage, inside Chrome | For the "back to search" key. Cleared when Chrome closes. |

Nothing ever leaves your browser through Feed Block.

## Permissions

| Permission | Why |
| --- | --- |
| Access to youtube.com, facebook.com, tiktok.com, instagram.com, x.com, twitter.com, reddit.com, linkedin.com, pinterest.com, snapchat.com, threads.com, and threads.net | To hide feeds on those sites. Feed Block runs only there. |
| `storage` | To save your settings. |
| `activeTab` | So the popup's "Allow this group" and "Allow this subreddit" buttons can read the address of the page you are on, only when you open the popup. |

## Contact

Questions: open an issue at https://github.com/TzTech26/Feed-Block-Privacy/issues
