+++
title = "Builder pattern efficiency"
date = 2024-02-20T22:20:03-08:00

[taxonomies]
tag = ["Rust", "Dev", "Design"]
via = ["Mastodon"]
+++

via [Rust Weekly 🦀 (@rust_discussions@mastodon.social)](https://mastodon.social/@rust_discussions/111966834135376587): Wrote a blog (and benchmark) different type of builder patterns in rust

A small benchmark repo comparing different ways to implement the builder pattern in Rust — owned `self`, `&mut self`, typestate, and friends. Handy data if you've ever wondered whether your builder's ergonomics come at a runtime cost.

<!-- more -->

[Builder pattern efficiency](https://github.com/atamakahere-git/bob)
