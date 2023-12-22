# List of Projects on Mina and o1js 

In this repository, you can find a list of zkApps and libraries related to Mina Protocol that are developed by Mina Foundation, O(1) Labs, and other ecosystem partners.

Please note that a zkApp or library may be listed in multiple files if it falls into multiple categories.

Please feel free to contribute to this repo by making a PR. Make sure you read [Contribution Guidelines](/README.md#contribution-guidelines) before creating your PR.

## Background Information

[Mina](https://minaprotocol.com/) is a layer-1 blockchain with a 22KB blockchain and ZK (zero knowledge) smart contracts (zkApps) written in [TypeScript](https://www.typescriptlang.org/).

[zkApps](https://docs.minaprotocol.com/zkapps) are ZK applications deployed on the Mina Protocol. They execute off chain, and their state update is verified by blockchain validators through ZK proofs. Mina zkApps support [private inputs](https://docs.minaprotocol.com/zkapps/o1js/smart-contracts#public-and-private-inputs) (inputs that are not seen by the blockchain, but still used inside smart contract methods), [recursion](https://docs.minaprotocol.com/zkapps/o1js/recursion) inside ZK proofs, and many other features to allow building very strong decentralized applications on Mina.

[o1js](https://www.npmjs.com/package/o1js) is a Typescript framework allowing ZK developers to create zkApps. It includes provable built in types and methods to create ZK proofs inside a browser. The compiled ZK proofs can be verified both on and off chain.

## Index

### zkApps

- [Bio Technology Related zkApps](/zkapps/biotech.md)

- [MINA Coin and Other Coin Projects](/zkapps/coin.md)

- [Credentials](/zkapps/credentials.md)

- [Exchanges (DEX) and Related Utilities](/zkapps/exchange.md)

- [Funding Platforms](/zkapps/funding.md)

- [Games on Mina](/zkapps/gaming.md)

- [Governance and Voting](zkapps/governance.md)

- [Launchpads](zkapps/launchpad.md)

- [Proof of Location](zkapps/location.md)

- [Machine Learning](zkapps/machine_learning.md)

- [NFT](/zkapps/nft.md)

- [Oracles](/zkapps/oracle.md)

- [Privacy Focused zkApps](/zkapps/privacy.md)

- [Social Networks](/zkapps/social.md)

- [Tokens](/zkapps/token.md)

- [Verification and Authenticity](/zkapps/verification.md)

- [Wallets and Wallet Related Utilities](/zkapps/wallet.md)

- [Miscellaneous (Other)](zkapps/miscellaneous.md)

### o1js and Mina Blockchain Contributions

- [Mina Community Benefit Platforms](/libraries/platforms.md)

- [Mina L2 Rollups and SDKs](/libraries/rollups.md)

- [ZK CLI Improvements and Utility Functions](/libraries/zkcli.md)

#### o1js Framework related Contributions

- [Bridges to Mina](/libraries/o1js/bridge.md)

- [o1js Development Environments](/libraries/o1js/environment.md)

- [Frontend o1js Packages](/libraries/o1js/frontend.md)

- [Off Chain Data Storage and Data Availability Solutions](/libraries/o1js/storage.md)

- [o1js Composite Types, Utility Functions, and Libraries](/libraries/o1js/utilility.md)

#### Mina Blockchain Contributions

- [Explorers](/libraries/mina/explorer.md)

- [Mina Node Extensions and Utilities](/libraries/mina/node.md)

## Contribution Guidelines

Contributions are more than welcome, but please be respectful to these contribution guidelines while making a PR to this repository.

1. All zkApps, libraries, or materials you add to a list must be in the [template format](/template.md).

2. All items must always be in alphanumerical order.

3. Please double check all the information you have provided is valid and up to date.

4. Make sure you have put the new item to the files of all related categories. For instance, a zkApp that is using ZKML inside an on chain game must be listed both below [machine_learning.md](/zkapps/machine_learning.md) and [gaming.md](/zkapps/gaming.md) files.

5. Please respect [O(1) Labs Contributing Guidelines](https://github.com/o1-labs/o1js/blob/main/CONTRIBUTING.md).