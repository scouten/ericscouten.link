+++
title = "sccache-action improves Rust build times"
date = 2023-10-17T17:15:00-07:00

[taxonomies]
tag = ["Dev", "GitHub", "Rust"]
via = ["Mastodon"]
+++

via [fasterthanlime 🌌](https://hachyderm.io/@fasterthanlime/111251695860293655): Holy fuck, migrating from the rust/cache action to the sccache action made macOS CI times (for a typical PR) fall from 9 minutes to 1 minute

<!-- more -->

GitHub: [hapsoc/fluke issue #118: Consider switching to sccache-action](https://github.com/hapsoc/fluke/issues/118)

_(Some good wisdom in the comment thread if you're facing long PR build times.)_
