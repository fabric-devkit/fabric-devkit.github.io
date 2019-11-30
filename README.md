# Overview

`Fabric Devkit` is a collection of demonstrator and experimental projects created by Paul Sitoh and David Carrington (i.e. the principal maintainers) to analyse the features and capabilities of Hyperledger Fabric.

## What can I expect from the Fabric Devkit?

You can use the `Fabric Devkit` projects to you learn about Hyperledger Fabric architecture and use cases. However, if I wanted to learn about Hyperledger Fabric, couldn't I just go to the [official Hyperledger Fabric document](https://hyperledger-fabric.readthedocs.io/en/release-1.4/blockchain.html)?

Firstly, `Fabric-Devkit` is not intended to replace the official document. It is to complement the official document or others materials.

Secondly, feedbacks to the `Fabric-Devkit` maintainers suggest that official document is "one-size-fits-all". If you are new to blockchain it is pretty tough to understand what Hyperledger Fabric is, let alone how to use it. `Fabric DevKit` projects were tailored to satisfy the learning objectives from the point of views of Platform (or DevOps or Site Reliability) Engineers, Application Developers and Product Owners.

| Role | Description |
| :--- | :--- |
| Platform Engineers | Anyone who is responsible for creating or using tools to automate the orchestration of infrastructure and middlewares. |
| Application Developers | Anyone who is involved in the creation of User Interfaces (UI) and integrating UI with middleware. |
| Product owners | Anyone who is member of an agile team who serves as the Customer proxy responsible for working with Product Management and other stakeholders—including other POs—to define and prioritize stories in the team backlog<sup>[1](https://www.scaledagileframework.com/product-owner/)</sup> |

Thirdly, by being independent of the official Hyperledger Fabric projects it gives the principal maintainers of the `Fabric-Devkit` the ability to share knowledge at a pace of their own choosing.

Fourthly, the best way to learn about a technology is to create and share stuff!

## How can I stuff in Fabric Devkit that interest me?

`Fabric Devkit` projects are categorised as `core`, `dev` or `demo`.

| Type | Description |
| --- | --- |
| Core | These projects demonstrate the inner workings of the core components of Hyperledger Fabric. |
| Dev | These projects  demonstrate the principles of developing apps interacting with Hyperledger Fabric|
| Demo | These projects demonstrate ways of implementing Hyperledger Fabric based solution to satisfy a given use case. |

Alternatively, you could try to find a `Personas` that matches you and follow the user stories associated with the persona. There are hypertext links that will leead you to aspects of `Fabric Devkit` that might interest you.

## Who maintains the Fabric Devkit?

* [https://fabric-devkit/core-platform](https://fabric-devkit/core-platform) is dedicated to demonstrating ways of assembling parts of Hyperledger Fabric components.

*Dev projects*

* [https://fabric-devkit/dev-chaincode-go](https://fabric-devkit/dev-chaincode-go) is deducated to demonstrating the core principles of writing chaincode in Go.

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

```text
Copyright (c) 2019. The Fabric-DevKit Authors. All rights reserved.
SPDX-License-Identifier: Apache-2.0
```

## Disclaimers

The projects hosted by and any views associated with `Fabric Devkit` are in most part based on Hyperledger Fabric projects. However, these are **NOT** and does **NOT** represents the views official Hyperledger Fabric. The views mentioned in `Fabric Devkit` projects belongs to the project contributors.
