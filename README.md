Pivotal Markdown Link (PMDL)
======

### 📖 WHAT IS IT

PMDL is a Chrome [Content Script Extension](https://developer.chrome.com/extensions/content_scripts) that places an extra button into [Pivotal Tracker](pivotaltracker.com) story card.

### 🚀 GET IT

The extension is available on the Chrome App Store. [Get it here!](https://chrome.google.com/webstore/detail/pivotal-markdown-link/kaegggniajpipbdjkhhmemjnilebjjpn)

### 🔎 EXAMPLE

![The best story in the world](https://cloud.githubusercontent.com/assets/442279/24854149/8e1922e6-1e07-11e7-89e4-2e3814b34bc7.png)

Clicking the button will copy a markdown link to the story to your clipboard and ready to paste into Github PR or wherever

Produces markdown links in the following format

```md
[{{ID}}]({{URL}}) {{NAME}}
```

For instance

```md
[#1337](https://www.pivotaltracker.com/story/show/1337) The best story in the world
```
