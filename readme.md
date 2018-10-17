wasm-gc required and rustup target wasm32-unknown-unknown set up as default

to compile
```
cargo build --target wasm32-unknown-unknown --release
wasm-gc target/wasm32-unknown-unknown/release/utils.wasm -o utils.gc.wasm
```

then using https library from  cargo (cargo install https) go to the index.html