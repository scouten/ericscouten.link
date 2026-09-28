+++
title = "Introducing Emit"
date = 2024-06-13T20:14:42-07:00

[taxonomies]
tag = ["Rust", "Dev", "OSS", "Infrastructure", "Diagnostics", "Observability"]
via = ["Mastodon"]
+++

via [Rust Weekly 🦀 (@rust_discussions@mastodon.social)](https://mastodon.social/@rust_discussions/112612347312240062): Introducing emit: developer-first diagnostics for Rust applications

Ashley Mannix introduces `emit`, a diagnostics framework for Rust that's been years in the making. Rather than following OpenTelemetry's data model, everything is a single primitive — an event, described by a message template — from which logs, trace spans, and metric samples are all built. It still plugs into OTLP collectors, rolling files, or a pretty-printed console when you want them.

<!-- more -->

[Introducing Emit](https://kodraus.github.io/rust/2024/06/13/introducing-emit.html)
