+++
title = "Rust Trick for Repetitive Documentation"
date = 2023-11-09T19:27:18-08:00

[taxonomies]
tag = ["Dev", "Rust"]
via = ["Mastodon"]
+++

via [Valentine Briese :transuwu:](https://hachyderm.io/@valentinegb/111379268533519239): Little bit of a trick I discovered for documenting fields which are on multiple structures:

<!-- more -->

```rust
macro_rules! extensions_doc {
    () => {
        r#"The extensions properties are implemented as patterned fields that are always prefixed by `"x-"`."#
    };
}

pub struct Info {
    // ...
    #[doc = extensions_doc!()]
    pub extensions: HashMap<String, Value>,
}
```
