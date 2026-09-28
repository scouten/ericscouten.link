+++
title = "Achieving Safe, Aliasable Mutability with Unboxed Types"
date = 2024-02-04T13:17:02-08:00

[taxonomies]
tag = ["Dev", "Rust"]
via = ["Mastodon"]
+++

via [Rust Weekly 🦀 (@rust_discussions@mastodon.social)](https://mastodon.social/@rust_discussions/111871987769598555): Achieving Safe, Aliasable Mutability with Unboxed Types

Jake Fecher explains how the Ante language aims to allow aliasable mutability without giving up memory or thread safety, using unboxed types to sidestep Rust's "Aliasability XOR Mutability" rule. A thoughtful look at one of the most common sources of friction in Rust's borrow checker and what a different set of tradeoffs might look like.

<!-- more -->

[Achieving Safe, Aliasable Mutability with Unboxed Types](https://antelang.org/blog/safe_shared_mutability/)
