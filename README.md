# Yogchain

<div style="text-align: center;">
    <img height="300" src="docs/assets/Yogchain_logo.png" alt="yogchain logo"/>
</div>

Yogchain is a Substrate-based EVM compatible network based on [Parity's Frontier pallet](https://github.com/paritytech/frontier).

You can run any Solidity smart contract in Yogchain, and use any Ethereum development environments including Hardhat, Truffle, Remix, and many more.

## Running the Yogchain Node

To run the Yogchain Node, you can firstly build it:

```
cargo build --release
```

Then run it:

```
./target/release/yognode --dev --enable-offchain-indexing true
```
