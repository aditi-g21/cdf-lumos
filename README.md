# Project Lumos

## Introduction To The Problem

The human experiences of those displaced by natural disasters are very traumatic. People displaced during it often lose family members, endure family separation, lose their possessions, and experience trauma and depression.

They have similar protection and assistance needs. They lose important documents which limits their access to public services. They lose property and it may take years (if ever) before they receive compensation for their loss.

Without connectivity, they can&#39;t do all the things people need to do after a disaster: ask for help and assure their loved ones that they are fine.

## Solution

To create a local network for people displaced during a natural disaster, we came up with the idea of using Hyperledger Fabric.

Hyperledger Fabric is an open source enterprise-grade permissioned distributed ledger technology (DLT) platform, designed for use in enterprise contexts, that delivers some key differentiating capabilities over other popular distributed ledger or blockchain platforms.

In its simplest form, a distributed ledger is a database held and updated independently by each participant (or node) in a large network. The distribution is unique: records are not communicated to various nodes by a central authority, but are instead independently constructed and held by every node. That is, every single node on the network processes every transaction, coming to its own conclusions and then voting on those conclusions to make certain the majority agree with the conclusions.

Distributed Ledgers are a dynamic form of media and have properties and capabilities that go far beyond static paper-based ledgers.

We decided to create a ledger for people displaced so that they can update information in it. One ledger will constitute of many ledgers of a person. It will contain information like,

- Name
- Age
- Current Location
- Identification Number
- Permanent Address
- Any additional information, etc.

The ledger will be updated by the people present in the network. It won&#39;t be designed to be open to the world but you can add as many entities as you want.

Hyperledger Fabric, being a permissioned platform, enables confidentiality through its channel architecture. Basically, participants on a Fabric network can establish a &quot;channel&quot; between the subset of participants that should be granted visibility to a particular set of transactions. Thus, only those nodes that participate in a channel have access to the smart contract (chaincode) and data transacted, preserving the privacy and confidentiality of both.
