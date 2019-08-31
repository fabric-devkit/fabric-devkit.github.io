# Overview

`Fabric Devkit` is a collection of projects created and shared as Open Source by Paul Sitoh and David Carrington (i.e. the principal maintainers). 

The projects started as a way for the principal maintainers to develop deep knowledge about Hyperledger Fabric by creating from scratch or analysing the internals of artefacts. The principal maintainers also decided to Open Source the propjects to share knowledge and solicit feedbacks.

## What can I expect from the Fabric Devkit?

The mission of `Fabric Devkit` is to help Platform (or DevOps or Site Reliability) Engineers, Application Developers and Product Owners gain knowledge about Hyperledger Fabric.

| Role | Description |
| :--- | :--- | 
| Platform Engineers | Anyone who is responsible for creating or using tools to automate the orchestration of infrastructure and middlewares. |
| Application Developers | Anyone who is involved in the creation of User Interfaces (UI) and integrating UI with middleware. |
| Product owners | Anyone who is member of an agile team who serves as the Customer proxy responsible for working with Product Management and other stakeholders—including other POs—to define and prioritize stories in the team backlog<sup>[1](https://www.scaledagileframework.com/product-owner/)</sup> |
[ Definition of platform engineers, application developers and product owners ]

Wait, if I wanted to learn about Hyperledger Fabric, couldn't I just go to the [official Hyperledger Fabric document](https://hyperledger-fabric.readthedocs.io/en/release-1.4/blockchain.html)?

Firstly, `Fabric-Devkit` is not intended to replace the official document. It is to complement the official document or others materials, unofficially.

Secondly, feedbacks to `Fabric-Devkit` maintainers suggest that official document is "one-size-fits-all". If you are new to blockchain it is pretty tough to understand what Hyperledger Fabric is about let alone how to use it. Also many of the examples provided by the official documentation mix multiple aspects of the technology together namely, platform engineering and application development. For product owners, who have only worked on traditional applications, the official documentation expects you to have experience working with decentralised system. The intention of `Fabric Devkit` is to help people with the different background to find learning route that is suited to their needs.

Thirdly, by being independent of the official Hyperledger Fabric projects and as practitioner of the lean startup methodology, it gives the principal maintainer of the `Fabric-Devkit` the ability to generate Minimum Viable Product (MVP) with minimum bureaucratic processes.

Fourthly, the best way to learn about a technology is to create and share stuff!

## How can I find a project that is suited for my learning needs?

`Fabric Devkit` projects are categorised as either `core` or `demo`.

| Type | Description |
| --- | --- |
| Core | These are projects created without any reference to specific domains such as Supply Chain, Cryptocurrencies, etc. They are typically projects intending to illustrate the underlying architecture of Hyperledger Fabric or productivity tools that can be used to support other projects. |
| Demo | These are projects created to illustrate one of many ways of implementing a given use case. |
[Definition of core or demo projects]

*Core projects*

Core projects are named `github.com/fabric-devkit/core-<domain>-<optional>`. The list of core projects are: 

* [https://fabric-devkit/core-platform](https://fabric-devkit/core-platform) is dedicated to demonstrating ways of assembling parts of Hyperledger Fabric components.
* [https://fabric-devkit/core-chaincode-go](https://fabric-devkit/core-chaincode-go) is deducated to demonstrating the core principles of writing chaincode in Go.

*Demo projects*

Demo projects are named `github.com/fabric-devkit/demo-<domain>-<optional>`. This listof demo projects are:

* [https://fabric-devkit/demo-ldap](https://fabric-devkit/demo-ldap) is dedicated to demonstrating the integration between an LDAP and Hyperledger Fabric

*Find projects by personas*

Alternatively, select on the left panel the item named `Personas`, then select the roles appropriate to yours and then select the persona that matches you. Follow the steps of activities describe in the persona.

## Who are the maintainers?

`Fabric Devkit` projects are based on contributions from volunteers collaborating on an ad hoc basis. 

The two principal contributors (maintainers) are Paul Sitoh and David Carrington, who are also the owner and administrator, respectively, of the Github repositories hosting the `Fabric Devikits`. They will be the final arbiters on the projects to be managed under the banner of `Fabric Devkits`.

## Can I contribute?

Yes, anyone is welcome to contribute but please abide by the contribution guidelines.

## Copyright notice

The copyrights to the projects belongs to the contributors. All projects are licensed under Apache 2.0 and attributed under this declaration:

```
Copyright (c) 2019. The Fabric-DevKit Authors. All rights reserved.
SPDX-License-Identifier: Apache-2.0
```

## Disclaimers

The projects hosted by and any views associated with `Fabric Devkit` are in most part based on Hyperledger Fabric projects. However, these are **NOT** and does **NOT** represents the views official Hyperledger Fabric. The views mentioned in `Fabric Devkit` projects belongs to the project contributors.