# zero2prod
Zero to production web service in Rust

## Tools
### [cargo-tarpaulin](https://github.com/xd009642/tarpaulin), a code coverage tool for Rust projects
```
cargo tarpaulin --ignore-tests
```

### [cargo clippy](https://github.com/rust-lang/rust-clippy), a bunch of lints to catch common mistakes and improve your Rust code
```
cargo clippy -- -D warnings
```

### [cargo fmt](https://github.com/rust-lang/rustfmt), format Rust code
```
cargo fmt -- --check
```

### [cargo-audit](https://github.com/RustSec/cargo-audit), audit Cargo.lock files for crates with security vulnerabilities
```
cargo audit
```

### [cargo-edit](https://github.com/killercup/cargo-edit), a utility for managing cargo dependencies from the command line
```
cargo add some_package --vers some_version
```

### [cargo-expand](https://github.com/dtolnay/cargo-expand), subcommand to show result of macro expansion
```
cargo expand
```