# Yogchain

Yogchain is a Substrate-based EVM compatible network based on [Parity's Frontier pallet](https://github.com/paritytech/frontier).

You can run any Solidity smart contract in Yogchain, and use any Ethereum development environments including Hardhat, Truffle, Remix, and many more.

## Running the Yogchain Node

To run the Yogchain Node, you can firstly build it:

```
cargo build --release
```

Then run it:

```
./target/release/appchain-barnacle --dev --enable-offchain-indexing true
```