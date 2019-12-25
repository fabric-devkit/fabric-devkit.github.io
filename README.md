# Overview

The `Fabric Devkit` started out as a project to create a toolkit to help developers developing solution based on Hyperledger Fabric version 1.0. There was a lack of toolkit that made it easy for developers to create solution for that version.

To support the creation of the toolkit, the creator and principal maintainers of `Fabric DevKit` (initially Paul Sitoh, and later joined by David Carrington) had to conduct experimentation to understand the inner workings and capabilities of Hyperledger Fabric. This led to the creation of demonstrators. As part of the learning process as well as soliciting feedback from the wider developers communities, the demonstrators were collected and group, culminating in the `Fabric DevKit` that is now shared as open sourced projects.

If you want to learn about Hyperledger Fabric through playing with interactive code, `Fabric DevKit` could just be the resource for you.

## What can I expect from the Fabric Devkit?

If you new to Hyperledger Fabric, please to the refer to the section on [key concepts](https://fabric-devkit.github.io/concepts.html).

Git clone the `Fabric Devkit` projects and use them to learn about the inner workings and use cases of Hyperledger Fabric. 

Wait, if you wanted to learn about Hyperledger Fabric, couldn't you just go to the [official Hyperledger Fabric document](https://hyperledger-fabric.readthedocs.io/en/release-1.4/blockchain.html)?

Firstly, `Fabric DevKit` is not intended to replace the official Hyperledger Fabric documentation. It is to complement the official document or others materials.

Secondly, `Fabric DevKit` projects are oragnised to satisfy learning objectives from the point of views of Platform (or DevOps or Site Reliability) Engineers, Application Developers and Product Owners (see definitions below) in bite-sized and fully functional demonstrators.

| Role | Description |
| :--- | :--- |
| Platform Engineers | Anyone who is responsible for creating or using tools to automate the orchestration of infrastructure and middlewares. |
| Application Developers | Anyone who is involved in the creation of User Interfaces (UI) and integrating UI with middleware. |
| Product owners | Anyone who is member of an agile team who serves as the Customer proxy responsible for working with Product Management and other stakeholders—including other POs—to define and prioritize stories in the team backlog<sup>[1](https://www.scaledagileframework.com/product-owner/)</sup> |

`Fabric DevKit` was created to avoid a one-size-fits-all demonstrator like the official [Build Your First Network demonstrator](https://hyperledger-fabric.readthedocs.io/en/release-1.4/build_network.html). The projects that make up the `Fabric DevKit` have been created to abstract out aspects that has no relevants and covers only aspects that have relevants to Platform Engineers, Application Developers and Product Owners respectively.

Thirdly, by being independent of the official Hyperledger Fabric project, it gives the principal maintainers of the `Fabric DevKit` the ability to share knowledge at a pace of their own choosing.

Fourthly, the best way to learn about a technology is to create and share stuff.

## Any prerequisite?

You will need some working knowledge of these technologies:

* Docker;
* Bash shell scripts.

## How can I find projects in Fabric Devkit that interest me?

You can search for the projects by [topics](https://fabric-devkit.github.io/topics.html) or by [persona](https://fabric-devkit.github.io/personas.html). See left panel.

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
