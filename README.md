# Rust WASM + WebGL + winit test

Goal is to get [A/B Street](abstreet.org) running on the web. And when `ezgui`
becomes a generally useful crate for anyone, let it be able to target web or
native.

```shell
cargo install cargo-web
cargo web start --target wasm32-unknown-unknown
```

Started from
https://github.com/rust-windowing/winit/blob/master/examples/web.rs and
https://github.com/grovesNL/glow/tree/master/examples/hello
