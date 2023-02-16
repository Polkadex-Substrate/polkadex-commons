## Type Defintion
```ts
    "id": string,  //genesis hash of the chain 
    "name": string, //name of the chain as shown in explorers
    "network_id": number, //the network id used by polkadex chain to interact. 0 is reserverd for polkadex
    "parachain_id": number, //the parachain id of the network. -1 means its not a parachain
    "token_ticker": string, //ticker for native token of the chain
    "token_decimals": number, // decimals for native token
    "signature_type": string, //signature validation used by chain can be sr25519 | ed25519 | ecdsa
    "chain_type": string, // type of the chain. values can be substrate | evm 
    "ss58": number, //address representation on substrate chain
    "url": "string, //url to the rpc of the chain
    "explorer_url": string, // url to the explorer website for the chain
    "is_main": boolean, //flag to see if network is a mainnet
    "evm_id": boolean,  //evm network id of the chain. -1 for non evm chains
```

