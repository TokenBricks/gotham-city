### Setup

1. You need [Rust](https://rustup.rs/) and [GMP library](https://gmplib.org) (optionally) to be installed on your computer.

### Launching the server
```bash
cd gotham-city/gotham-server
cargo run --release
```

### Integration tests
Open a new terminal and run:
```sh
cd gotham-city/integration-tests
$ cargo test
```