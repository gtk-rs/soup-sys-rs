# soup-sys [![Build Status](https://travis-ci.org/gtk-rs/soup-sys-rs.png?branch=master)](https://travis-ci.org/gtk-rs/soup-sys-rs) [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/gtk-rs/gtk)

[Project site](https://gtk-rs.org/) | [Online documentation](https://gtk-rs.org/docs/)

__Rust__ bindings and wrappers for __libsoup__.

## Using

We recommend using [crates from crates.io](https://crates.io/keywords/gtk-rs),
as [demonstrated here](https://gtk-rs.org/#using).

If you want to track the bleeding edge, use the git dependency instead:

```toml
[dependencies]
soup-sys = { git = "https://github.com/gtk-rs/soup-sys-rs.git" }
```

Avoid mixing versioned and git crates like this:

```toml
# This will not compile
[dependencies]
gtk = "0.2"
soup-sys = { git = "https://github.com/gtk-rs/soup-sys-rs.git" }
```

## Contribute

Contributor you're welcome!

## License

__soup-sys__ is available under the MIT License, please refer to it.
