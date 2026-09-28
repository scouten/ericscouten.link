+++
title = "Durable execution with Flawless and Rust"
date = 2024-10-04T09:33:02-07:00

[taxonomies]
tag = ["Rust", "Dev", "Infrastructure", "OSS"]
via = ["Mastodon"]
+++

via [Rust Weekly 🦀 (@rust_discussions@mastodon.social)](https://mastodon.social/@rust_discussions/113249365856800875): Introduction to durable execution with Flawless and Rust

Flawless is a durable execution engine for Rust: workflows that run to completion even when the process is killed mid-flight. Instead of hand-rolling a state machine with resume rules and idempotence guarantees around every external API call, you write plain business logic and let the engine handle the replay. Currently in beta 3.

<!-- more -->

[Durable execution with Flawless and Rust](https://flawless.dev/docs/)
