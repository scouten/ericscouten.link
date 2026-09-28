+++
title = "Rust data structures with circular references - Eli Bendersky's website"
date = 2024-03-26T21:59:30-07:00

[taxonomies]
tag = ["Rust", "Dev", "Design"]
+++

Eli Bendersky walks through why the "obvious" approach to parent pointers in a Rust tree fights the borrow checker, then works through the practical alternatives: Rc/Weak pairs, RefCell for interior mutability, and arena allocation with index-based links. A good reference for the moment you hit this wall in your own code.

<!-- more -->

[Rust data structures with circular references - Eli Bendersky's website](https://eli.thegreenplace.net/2021/rust-data-structures-with-circular-references/)
