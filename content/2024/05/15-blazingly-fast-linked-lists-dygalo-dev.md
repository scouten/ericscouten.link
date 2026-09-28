+++
title = "Blazingly Fast Linked Lists | dygalo.dev"
date = 2024-05-15T23:34:37-04:00

[taxonomies]
tag = ["Rust", "Dev", "Performance", "JSON"]
via = ["Mastodon"]
+++

via [Rust Weekly 🦀 (@rust_discussions@mastodon.social)](https://mastodon.social/@rust_discussions/112443888626427990): Blazingly Fast Linked Lists

Linked lists are usually an interview trivia question rather than a practical tool, but Dmitry Dygalo shows a case where they genuinely beat `Vec`: tracking the current location during JSON Schema validation so errors can point at the exact spot in the instance. The post walks through a series of optimizations drawn from real work on the `jsonschema` crate, measuring the impact of each step.

<!-- more -->

[Blazingly Fast Linked Lists | dygalo.dev](https://dygalo.dev/blog/blazingly-fast-linked-lists/)
