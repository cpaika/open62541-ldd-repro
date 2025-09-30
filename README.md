A reproduction of an LDD linker issue with Rust 1.90.0 and open62541.

To run on mac:
```brew install cmake
cargo build
```

The failure only occurs on x86 linux (where LDD is now the default linker).

