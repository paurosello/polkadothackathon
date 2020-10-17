# Commands

## Activate cargo
source ~/.cargo/env

## Download dev hub
git clone https://github.com/substrate-developer-hub/substrate-node-template.git
cd substrate-node-template

## Build
cargo +nightly build --release

## Test node
./substrate-node-template/target/release/node-template --ws-port 9945 --rpc-port 9946 --port 9947
./substrate-node-template/target/release/node-template purge-chain