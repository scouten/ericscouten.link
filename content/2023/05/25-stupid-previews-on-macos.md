+++
title = "Stupid previews on MacOS"
date = 2023-05-25T19:32:40-07:00

[taxonomies]
tag = ["Mac"]
via = ["Mastodon"]
+++

via [Craig Hockenberry](https://mastodon.social/@chockenberry/110386586751278042): Where there's a will, there's a way. To disable movie, PDF, and other useless previews, but still maintain the image on the icon, use this from Terminal:

<!-- more -->

```
$ defaults write com.apple.finder QLInlinePreviewMinimumSupportedSize -int 512
```

Then relaunch the Finder.

Halle-fricken-lujah!
