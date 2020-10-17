## Activate cargo
source ~/.cargo/env

# Node

## Download dev hub
git clone https://github.com/substrate-developer-hub/substrate-node-template.git
cd substrate-node-template

## Build
cargo +nightly build --release

## Test node
./substrate-node-template/target/release/node-template --ws-port 9945 --rpc-port 9946 --port 9947
./substrate-node-template/target/release/node-template purge-chain

## Follow tutorial
https://substrate.dev/docs/en/tutorials/add-contracts-pallet/

### Modify Runtime
Do runtime modifications
#### Check compilation
cargo +nightly check -p node-template-runtime

### Modify Node
Do node modifications
#### Build Node
cargo +nightly build --release
#### Execute Node
./target/release/node-template --dev --tmp --ws-port 9945 --rpc-port 9946 --port 9947


# Contract

https://substrate.dev/substrate-contracts-workshop/#/2/introduction

## Create Contract
cargo contract new erc20contract

## Modify flipper contract
- Implement ERC20 template
- Implement token transfer

## Test Contract
cargo +nightly test