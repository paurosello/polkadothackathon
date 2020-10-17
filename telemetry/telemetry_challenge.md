Download presynced DB from https://dotleap.com/how-to-import-a-pre-synced-kusama-database/

7z x QmdZrFRRCpgQoZZaGiCPAsQNiR1siVjSwpMtiq7CRTHBfh -o~/.local/share/polkadot/chains/ksmcc3

./polkadot --chain=kusama --name "paurosello-node" --pruning=archive --wasm-execution=compiled

╰─>$ ./polkadot --chain=kusama --name "paurosello-node" --pruning=archive --wasm-execution=compiled
Oct 16 21:06:24.817  INFO ----------------------------    
Oct 16 21:06:24.817  INFO This chain is not in any way    
Oct 16 21:06:24.817  INFO       endorsed by the           
Oct 16 21:06:24.817  INFO      KUSAMA FOUNDATION          
Oct 16 21:06:24.817  INFO ----------------------------    
Oct 16 21:06:24.817  INFO Parity Polkadot    
Oct 16 21:06:24.817  INFO ✌️  version 0.8.25-3094e8d2-x86_64-linux-gnu    
Oct 16 21:06:24.817  INFO ❤️  by Parity Technologies <admin@parity.io>, 2017-2020    
Oct 16 21:06:24.817  INFO 📋 Chain specification: Kusama    
Oct 16 21:06:24.817  INFO 🏷 Node name: paurosello-node    
...