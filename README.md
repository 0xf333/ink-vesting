# Vesting smart contract
General purpose vesting smart contract written in `ink!` 

## Prerequisites
- Rust

## Install ink contract compiler
```bash
rustup component add rust-src && cargo install --force --locked cargo-contract
```

## Compile the vesting contract

Navigate to the vesting directory
```bash
cd vesting 
```
and then compile the contract.
```bash
cargo vesting contract build
```
1. Build artifacts will be located in `target/ink` directory.
2. Use `vesting.contract` file to deploy the contract.
3. See code comments for detials on how each public function works.

### Note :
**This smart contract should be audited before deploying to mainnet.**