+++
title = "Designing error types in Rust libraries | Roman Kashitsyn"
date = 2024-03-05T19:31:51+00:00

[taxonomies]
tag = ["Rust", "Dev", "Design"]
via = ["Work"]
+++

Roman Kashitsyn lays out a set of goals for designing error types in Rust libraries: prefer specific enums over catch-all types, reserve panics for genuine bugs, lift input validation out of fallible calls, and embed rather than wrap underlying errors. The unifying theme is empathy — design the error type you'd want to handle as a caller.

<!-- more -->

[Designing error types in Rust libraries | Roman Kashitsyn](https://mmapped.blog/posts/12-rust-error-handling)
