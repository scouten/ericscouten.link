+++
title = "CodSpeed: Continuous Performance Testing for Your CI"
date = 2024-01-02T13:36:12-08:00

[taxonomies]
tag = ["Dev", "Rust", "Infrastructure", "GitHub", "OSS"]
via = ["Mastodon"]
+++

via [Jan (@janpio@hachyderm.io)](https://hachyderm.io/@janpio/111687543622549500): @scouten@ericscouten.social we have been trying https://codspeed.io/ for that use case. Works decently. Check github/prisma/prisma-engines PRs for examples.

CodSpeed runs benchmarks as part of CI and flags performance regressions directly in the pull request, using instrumentation rather than wall-clock timing so results aren't drowned out by noisy shared runners. It supports Rust, Python, Node, and Go, and several open source projects use it to keep an eye on performance drift over time.

<!-- more -->

[CodSpeed: Continuous Performance Testing for Your CI](https://codspeed.io/)
