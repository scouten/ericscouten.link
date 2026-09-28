+++
title = "My Best and Worst Deadlock in Rust"
date = 2024-01-20T10:37:12-08:00

[taxonomies]
tag = ["Rust", "Dev"]
via = ["Mastodon"]
+++

via [Rust Weekly 🦀 (@rust_discussions@mastodon.social)](https://mastodon.social/@rust_discussions/111788469431630382): My Best and Worst Deadlock in Rust

Michael Snoyman walks through building a subtle Rust deadlock step by step, using an RwLock-guarded struct and a seemingly innocent read-then-write pattern. It's the "worst" deadlock because it hides in plain sight, and the "best" because the tooling pointed straight at the culprit. Worth reading even if you think you know Rust's concurrency rules.

<!-- more -->

[My Best and Worst Deadlock in Rust](https://www.snoyman.com/blog/2024/01/best-worst-deadlock-rust/)
