# To run the project

Install wasm-pack :
```sh
cargo install wasm-pack
```

Install cargo generate :
```sh
cargo install cargo-generate
```

WebAssembly project are lib projects in Rust :

```sh
cargo new wasm_log_extractor --lib
```

Build command :
```sh
wasm-pack build --target web
```

Then open the index.html with VS Code Live Server extension.
