# rust-turbine-prereqs

Rust prerequisites for the Solana Turbin3 builders program, written as tests against devnet with `solana-sdk` and `solana-client`.

Covers keypair generation, converting between base58 and byte-array keys, requesting an airdrop, transferring SOL (including emptying a wallet after the fee), and calling the prerequisite program.

## Run

```bash
cargo test -- --nocapture
```

Run one step at a time with `cargo test <name> -- --nocapture`.

Stack: Rust 2021, `solana-sdk 2.0`, `solana-client 2.0`, `bs58`. Devnet only. Keep keypair files out of git.
