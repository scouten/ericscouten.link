+++
title = "mkdocs: Make a unified, searchable documentation set"
date = 2023-07-05T07:46:36-07:00

[taxonomies]
tag = ["Dev", "Docs", "GitHub", "Markdown"]
via = ["Mastodon"]
+++

via [Christie Koehler](https://toot.cat/@christi3k/110656979167526071): Oh! That reminds me to share something I’ve found super useful at work. If you’re in a situation where a team’s docs are in markdown spread across a bunch of git repos and you want a unified, searchable interface: mkdocs is your friend.

<!-- more -->

In a new git repo I add all the repos I want in the unified docs as git submodules. Them I use mkdocs to generate unified docs that I render with GH pages.

Doesn’t interfere with original docs at all.

[MkDocs: Project documentation with Markdown](https://www.mkdocs.org/)
