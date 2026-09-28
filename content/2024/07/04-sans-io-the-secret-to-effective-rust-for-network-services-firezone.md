+++
title = "sans-IO: The secret to effective Rust for network services | Firezone"
date = 2024-07-04T08:07:31-07:00

[taxonomies]
tag = ["Rust", "Dev", "Infrastructure", "Design"]
via = ["Mastodon"]
+++

via [Thomas (@wheezle@hachyderm.io)](https://hachyderm.io/@wheezle/112726080292898713): Been writing code in the sans-IO style for a while now and really enjoying it so I wrote up a blog post about it! #rustlang

Firezone's Thomas Eizinger explains the sans-IO pattern: implementing network protocols as pure state machines that never touch a socket or call `Instant::now` themselves, leaving all IO and timing to the caller. The payoff is fast, exhaustive, deterministic tests and a way to sidestep the "function colouring" problem — async ends up confined to a thin outer layer instead of infecting the whole stack.

<!-- more -->

[sans-IO: The secret to effective Rust for network services | Firezone](https://www.firezone.dev/blog/sans-io)
