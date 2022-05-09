# Tokenizer zkSync

To compile contracts run:
```sh
yarn hardhat compile
```

### Problems

`master` branch contains all compilable contracts. First contract that couldn't compile is `Asset.sol` check out `asset` and try to compile to see error.

## Deployment

For deploying contracts see file: `./deploy/deploy.ts` and replace `<PRIVATE_KEY>` with the 0x-prefixed private key of your Ethereum wallet wallet with some Görli ETH on L1. 
Run the script using the following command:
```sh
yarn hardhat deploy-zksync
```

### Deployed contracts

`ApxAssetsRegistry.sol` contract is deployed on testnet: [0x34723AAF092081d4c644247BA191FC0d5681E75E](https://zksync2-testnet.zkscan.io/address/0x34723AAF092081d4c644247BA191FC0d5681E75E/transactions)

## References

- https://v2-docs.zksync.io/api/hardhat/getting-started.html#initializing-the-project 
