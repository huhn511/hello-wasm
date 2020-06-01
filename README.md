# hello-wasm

run
```
cargo run
```


build 
```
cargo build --target=wasm32-wasi --release
```

run with [wasmtime](https://github.com/bytecodealliance/wasmtime)
```
wasmtime --dir=. target/wasm32-wasi/release/main.wasm
```

run with [wapm](https://wapm.io/)
```
wapm run greet
```