# Awesome Mina

In this repository, you can find a list of zkApps and libraries related to Mina Blockchain that are developed by Mina Foundation, O(1) Labs, and community members.

Please note that a zkApp or library may be listed in multiple files if it falls into multiple categories.

Please feel free to contribute to this repo by making a PR. Make sure you read [Contribution Guidelines](/README.md#contribution-guidelines) before creating your PR.

## Background Information

[Mina Blockchain](https://minaprotocol.com/) is a _fully decentralized_ L1 with ZK (zero knowledge) programmability. It is a **constant sized** blockchain: The entire Mina state is 22 KBs.

[zkApps](https://docs.minaprotocol.com/zkapps) are ZK applications deployed on the Mina Blockchain. They execute client side, and their state update is verified by blockchain validators through ZK proofs. Mina zkApps support [private inputs](https://docs.minaprotocol.com/zkapps/o1js/smart-contracts#public-and-private-inputs) (inputs that are not seen by the blockchain, but still used inside smart contract methods), [recursion](https://docs.minaprotocol.com/zkapps/o1js/recursion) inside ZK proofs, and many other features to allow building very strong decentralized applications on Mina.

[o1js](https://www.npmjs.com/package/o1js) is a Typescript framework allowing ZK developers to create zkApps. It includes provable built in types and methods to create ZK proofs inside a browser. The compiled ZK proofs can be verified both on and off chain.

## Contribution Guidelines

Contributions are more than welcome, but please be respectful to these contribution guidelines while making a PR to this repository.

1. All zkApps, libraries, or materials you add to a list must be in the [template format](/template.md)

2. All items must always be in alphanumerical order.

3. Please double check all the information you have provided is valid and up to date.

4. Make sure you have put the new item to the files of all related categories. For instance, a zkApp that is using ZKML inside an on chain game must be listed both below machine_learning and gaming files.

5. Please respect [O(1) Labs Contributing Guidelines](https://github.com/o1-labs/o1js/blob/main/CONTRIBUTING.md).