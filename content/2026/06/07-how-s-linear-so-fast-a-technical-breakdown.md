+++
title = "How's Linear so fast? A technical breakdown"
date = 2026-06-07T20:10:59-07:00

[taxonomies]
tag = ["Dev", "Web", "Database", "JavaScript", "Design"]
via = ["Mastodon"]
+++

via [Hacker News 100 (@hn100@social.lansky.name)](https://social.lansky.name/@hn100/116710736513486852): How's Linear so fast? A technical breakdown

Dennis Brotzky reverse-engineers the architectural decisions that make Linear feel instantaneous: a real database (IndexedDB) in the browser, local-first mutations that render synchronously, and a sync engine that pushes deltas over WebSockets in the background. It's a good tour of the local-first playbook — the core insight being that the fastest network request is the one you never make.

<!-- more -->

[How's Linear so fast? A technical breakdown](https://performance.dev/how-is-linear-so-fast-a-technical-breakdown)
