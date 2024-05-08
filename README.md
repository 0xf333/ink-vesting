# Vesting smart contract

## Prerequisites
- Rust

## Install ink contract compiler
```bash
rustup component add rust-src && cargo install --force --locked cargo-contract
```

## Compile the vesting contract
```bash
cargo contract build
```
1. Build artifacts will be located in `target/ink` directory.
2. Use `vesting.contract` file to deploy the contract.