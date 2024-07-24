# Brainstems Smart Contract
This is the repository of the Brainstems smart contract. Symbol `STEMS`. Standard `NEP-141` (ERC20 equivalent).

## Installing dependencies
```npm i -g near-cli```

## Building
```cargo near build```

## Deploying
Deploying to Testnet
```near deploy <account> <wasm smart contract file>```
or
```cargo near deploy <account Id> with-init-call new_default_meta json-args '{"owner_id": "'<account Id>'", "total_supply": "0"}' prepaid-gas '100.0 Tgas' attached-deposit '0 NEAR' network-config testnet sign-with-keychain send```

## Check for contract metadata
```near view <account> ft_metadata```
