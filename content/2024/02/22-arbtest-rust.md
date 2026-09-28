+++
title = "arbtest - Rust"
date = 2024-02-22T07:07:05-08:00

[taxonomies]
tag = ["Rust", "Dev", "OSS"]
via = ["Mastodon"]
+++

via [Rust Weekly 🦀 (@rust_discussions@mastodon.social)](https://mastodon.social/@rust_discussions/111973910043050380): arbtest — powerfully tiny property-based testing

arbtest is a property-based testing library for Rust with a refreshingly tiny API: one function, no macros. It takes an `arbitrary::Unstructured` random data source, shrinks failures automatically, and prints a seed you can use to deterministically replay any failure — plus it supports time budgeting and works with fuzzers.

<!-- more -->

[arbtest - Rust](https://docs.rs/arbtest/0.3.0/arbtest/index.html)
