+++
title = "Optimize Rust code by avoiding panics"
date = 2023-10-05T05:18:10-07:00

[taxonomies]
tag = ["Dev", "Rust"]
via = ["Mastodon"]
+++

Via [Rust tips](https://octodon.social/@rust/111179245721227273): If you want your #Rustlang code to be fast and compact, avoid code that could panic.

<!-- more -->

> Returning from a function instead of panicking is always going to optimize better.

Compiler Explorer: [Sample code showing disassembly of return vs panic](https://rust.godbolt.org/z/MKW1xjrrx)
