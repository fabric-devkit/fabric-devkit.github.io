---
title: Key Concepts
nav_order: 2
---

## Key Concepts

From a very high level perspective, Hyperledger Fabric, according to its official document is a "platform for distributed ledger solutions" and sometimes referred to as a Blockchain platform. However, what exactly is a distributed ledger or blockchain and what problem is Hyperledger Fabric intended to solve?

The answers to these questions can be found the [official documentation](https://hyperledger-fabric.readthedocs.io/en/release-1.4/blockchain.html). However, for the purpose of appreciating the intention behind `Fabric Devkit`, we'll focus on these core aspects of Hyperledger Fabric architecture:

* Nodes;
* Transactions;
* Ledger (or blockchain);
* World states;
* Orderer;
* Identity, Membership Service Provider (MSP) and Certificate Authority (CA);
* Chaincode;
* Networks, organisations and channels;
* Consensus and transactional finality.

## Nodes, transactions, ledger, world states and orderer

A distributed ledger is not dissimilar to a distributed computing system, where you have a `client node` (a User Interface) sending instructions or transactions to a backend or server node (known in Hyperledger Fabric speak as a `peer node`).

In conventional distributed computing system nodes process the instruction and updates some datastore (Hyperledger Fabric equivalent is known as `World State`), upon receipt of a transaction.

In the case of Hyperledger Fabric, transactions have to be crypographically signed and the peer nodes are responsible for ensuring that the signature is valid. The peer node is also responsible for ensuring that when it process any transaction, it will be able produce results that are consistent with results of previous ones (the combination of these steps are known as `endorsement`).

Following endorsement, peers sent transactions to the `orderer` who is responsible for packing transactions into a block and is also reponsible for linking blocks cryptographically to form a chain of blocks (also known as the `ledger`). The latest block is then sent out all peer nodes in the Hyperledger Fabric network. The receiving peers will be responsible executing transactions in the block, committing results of transactions in the `world state` and adding the block to the ledger.

## Identity, MSP and CA

All transactions process by Hyperledger Fabric peer node has to be signed with valid keys that are encoded in digital certificates. These items are stored in a special compartment known as a `Membership Service Provider`(MPS), which is used in all Hyperledger Fabric component for the identity purposes. A detailed explanation of how Hyperledger Fabric deals with identity please refer to this [blog](https://medium.com/@kctheservant/identity-in-hyperledger-fabric-94d06439816e).

A key component involved in the generation of artefacts, such as crytographic keys and digital certificates, used for identity purposes is Certificate Authority (CA). If you new to the concept of digital certificates and CA, please refer to this [how Digital Certificates work](https://www.youtube.com/watch?v=heacxYUnFHA) then please also refer to this [blog](https://medium.com/@kctheservant/exploring-fabric-ca-registration-and-enrollment-1b9f4a1b3ace) to understand the relationship between Hyperledger Fabric CA and client nodes.

## Chaincodes

A transaction in the context of Hyperledger Fabric is essentially a function call comprising of a name to indicate it's intent (e.g. pay) and function arguments (e.g. name of payee, amount and payer).

When a transaction is sent to a peer node, the piece of code that is responsible for processing the transactions is known as `chaincode`.

## Networks and channels

A Hyperledger Fabric node rarely and cannot operate on its own. At a minimum, there'll be at least one client node, one peer node, a CA and an orderer. A combination of nodes and CA could grouped under one domain to form a `organisation`. An other combination could constitute another organisation. One or more orderers would be cluster under its own organisation. All organisations when network together under a top level domain is known as a `network`.

Hyperledger Fabric network can also be effectively subnet to facilitate messaging between subsets of organisations. This is done through a mechanism known as `channels`.

Please refer to this [blog](https://medium.com/hyperlegendary/understanding-hyperledger-fabrics-architecture-3b37d81c3e96) for an architecture overview.

## Consensus and transactional finality

In a Fabric network, the job of endorsing and sequencing transactions into ledger is decentralised; all peers capture transactions independent of each other in a network. 

The job of ensuring that are peers provides a common view (i.e. reach a `consensus`) of the ledger is based on endorsement from at least one or more peers and the orderer who is reponsible for ordering the blocks and transactions.

Having reached consensus on the sequencing of transactions and blocks, the last stage of is to commit the results of the transactions in the world state. When the a transaction is committed to all peers, the transaction is said to have achieved `transactional finality`.
