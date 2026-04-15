+++
title = "oklch() retains perceived lightness for different hue angles"
date = 2023-11-26T17:57:52-08:00

[taxonomies]
tag = ["CSS", "Web", "Design"]
via = ["Mastodon"]
+++

via [Stefan Judis (@stefan@front-end.social)](https://front-end.social/@stefan/111478298771596871): A clear visual demonstration of why `oklch()` should replace `hsl()` for CSS color palettes: when you rotate the hue angle, `oklch()` maintains consistent perceived lightness while `hsl()` can shift dramatically. The interactive examples make the difference immediately obvious.

<!-- more -->

[`oklch()` retains perceived lightness for different hue angles | Stefan Judis Web Development](https://www.stefanjudis.com/today-i-learned/oklch-perceived-lightness/)
