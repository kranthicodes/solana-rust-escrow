# Solana Escrow program

This Rust program is for Escrow service on solana chain that involves three parties to carry out token exchange. 

Party A(Sends Token X to Party C), Party C(Holds tokens from Party A and B and does the exchange), Party B(Sends token Y to Party C).

## Description

This escrow program is a contract written in Rust, a programming language used for developing smart contracts on the Solana blockchain. 

The contract is composed of `lib.rs`(exposes all other files), `entrypoint.rs`(entry point of the program that forwards the instructions to processor), `processor.rs` uses `instruction.rs` and `state.rs` to decode or encode information and carries out the instruction.