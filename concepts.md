---
title: Key Concepts
nav_order: 2
---

## Overview

There are several terms and concepts that are unique to Hyperledger Fabric which `Fabric DevKit` is based. Please refer to the official documentation for a detailed explanation of the terms used. For the purpose of `Fabric DevKit`, we summarised some of the key terms used and these are:

| Terms | Definition |
| --- | --- |
| Chaincode | A Go, Node or Hyperledger Fabric support code installed on peer node to enable it to perform computation |
| Channel | A subnet of a Fabric network. |
| Client node | A type of node serving as an interface between a human user and a peer node |
| Fabric network | A network of a grouping of client, peer and ordering nodes. Each grouping is typically owned by a participant |
| Fabric Organisation (or Organisation) | A grouping of nodes identified by a root domain with each node in the grouping identified by sub-domain |
| Ledger | A series of timed transactions recorded in blocks that are cryptographically linked. |
| Node | A node a generalised term for computing platform responsible for processing blockchain ledgers, handling interactions with human users and enabling the blockchain network to reach consensus. |
| Participant | This refer to an entity typically an real world organisation or even a individual owning a collection of computing nodes |
| Peer node | A type of node responsible for validating transactions sent from client nodes. |
| Ordering node | A type of node responsible for taking transactions of a client node and packing it into a block and sending the block to the peer node to update the world state. |
| World state | A world state is datastore found in peer nodes representing the state generated from the clumination of transactions found in the ledger. All peers in the same channel share the same state or data structure and should have the same value for a given time frame -- i.e. consensus view. |

![A Hyperledger Fabric Network](https://vitalflux.com/wp-content/uploads/2017/12/hyperledger-fabric-channel-example-1.png "A Hyperledger Fabric Network.")

NOTE: In the above diagram, the red and blue ledger notations represents different channels of a given Fabric Network. E0. E1, E2 and E3 represents peer nodes.

## [Key concepts from official documentation](https://hyperledger-fabric.readthedocs.io/en/release-1.4/key_concepts.html)

* [Introduction](https://hyperledger-fabric.readthedocs.io/en/release-1.4/blockchain.html).
* [Hyperledger Fabric Functionalities](https://hyperledger-fabric.readthedocs.io/en/release-1.4/functionalities.html).
* [Hyperledger Fabric Model](https://hyperledger-fabric.readthedocs.io/en/release-1.4/fabric_model.html).
* [Blockchain network](https://hyperledger-fabric.readthedocs.io/en/release-1.4/network/network.html).
* [Identity](https://hyperledger-fabric.readthedocs.io/en/release-1.4/identity/identity.html).
* [Membership](https://hyperledger-fabric.readthedocs.io/en/release-1.4/membership/membership.html).
* [Peers](https://hyperledger-fabric.readthedocs.io/en/release-1.4/peers/peers.html).
* [Smart Contracts and Chaincode](https://hyperledger-fabric.readthedocs.io/en/release-1.4/smartcontract/smartcontract.html).
* [Ledger](https://hyperledger-fabric.readthedocs.io/en/release-1.4/ledger/ledger.html).
* [The Ordering Service](https://hyperledger-fabric.readthedocs.io/en/release-1.4/orderer/ordering_service.html).
* [Private data](https://hyperledger-fabric.readthedocs.io/en/release-1.4/private-data/private-data.html).
* [Channel capabilities](https://hyperledger-fabric.readthedocs.io/en/release-1.4/capabilities_concept.html).

## Additional reading materials

* [Blogs by KC Tam](https://medium.com/@kctheservant)
* [What are the differences between Ethereum, Hyperledger Fabric and Hyperledger Sawtooth?](https://medium.com/coinmonks/what-are-the-differences-between-ethereum-hyperledger-fabric-and-hyperledger-sawtooth-5d0fc279d862)
* [Hyperledger Fabric- The Most Popular Hyperledger Framework](https://hackernoon.com/hyperledger-fabric-the-most-popular-hyperledger-framework-b4485dea6a2c)

## Copyright Notice

Copyright (c) 2019. The Fabric-DevKit Authors. All rights reserved.
SPDX-License-Identifier: Apache-2.0
