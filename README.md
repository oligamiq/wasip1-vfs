# TODO!
- Support non-binary Wasm modules
- Enable specifying multiple Wasm modules
- Allow omitting Wasm file specifications
- support flush sync to file system
- rm export func by glob
- Wasm export/import definitions callable from VFS side
- adjust test_run.ts to use VFS

# run example
```bash
cargo r -- -p example_vfs examples/test_wasm/test_wasm_opt.wasm
```

# cannot
- support wasm-bindgen
  because it cannot use wasi

# non goal

# goal

