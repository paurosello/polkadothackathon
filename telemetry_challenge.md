Download presynced DB from https://dotleap.com/how-to-import-a-pre-synced-kusama-database/

7z x QmdZrFRRCpgQoZZaGiCPAsQNiR1siVjSwpMtiq7CRTHBfh -o ~/.local/share/polkadot/chains/ksmcc3

./polkadot --chain=kusama --name "paurosello-node" --pruning=archive --wasm-execution=compiled