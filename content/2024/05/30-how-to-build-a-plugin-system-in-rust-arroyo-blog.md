+++
title = "How to build a plugin system in Rust | Arroyo blog"
date = 2024-05-30T11:07:40-07:00

[taxonomies]
tag = ["Rust", "Dev", "SQL", "WASM"]
via = ["Mastodon"]
+++

via [Rust Weekly 🦀 (@rust_discussions@mastodon.social)](https://mastodon.social/@rust_discussions/112528828400473920): Building a dynamically-linked plugin system in Rust

Micah Wylde walks through how Arroyo, a real-time SQL engine, supports user-defined functions in a language that really wants to produce static binaries. He weighs scripting languages, out-of-process RPC, and Wasm before landing on dynamically-linked shared libraries with a C ABI, then digs into the details of designing safe FFI types and interfaces. A great read if you've ever wondered how to make a Rust program extensible at runtime.

<!-- more -->

[How to build a plugin system in Rust | Arroyo blog](https://www.arroyo.dev/blog/rust-plugin-systems)
