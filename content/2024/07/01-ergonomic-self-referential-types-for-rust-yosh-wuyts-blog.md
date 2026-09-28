+++
title = "Ergonomic Self-Referential Types for Rust — Yosh Wuyts — Blog"
date = 2024-07-01T08:34:01-07:00

[taxonomies]
tag = ["Rust", "Dev", "Design"]
via = ["Mastodon"]
+++

via [yosh (is out of office) (@yosh@toot.yosh.is)](https://toot.yosh.is/@yosh/112710376586461712): New blog post: Ergonomic Self-Referential Types for Rust

Yosh Wuyts sketches what it would take to make self-referential types in Rust genuinely ergonomic: `'self` lifetimes, in-place construction, an `!Move` marker in the type system, and safe phased initialization without the option-dance. It's an early exploration rather than a finished design, but it's a useful map of how several proposed features could combine to replace the awkwardness of `Pin`.

<!-- more -->

[Ergonomic Self-Referential Types for Rust — Yosh Wuyts — Blog](https://blog.yoshuawuyts.com/self-referential-types/)
