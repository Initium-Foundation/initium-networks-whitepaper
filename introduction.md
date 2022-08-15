# Introduction

Initium is an open-source platform for launching decentralized applications and enterprise blockchain deployments in one interoperable, highly scalable ecosystem. Initium benefits from a multi-layered architecture and a unique consensus protocol called Covenant that enables high-performance and scalable decentralized applications with ultra-low-cost transaction fees.

Initium is built on Rust language, which enables parallel runtime and low-cost computation and enables the developers to deploy complex programs using the LLVM, WebAssembly, and Initium technology.

While built on Rust, Initium aims to be an EVM-compatible blockchain by introducing the Castor network, an L2 network of the Initium blockchain enabling the developers to launch Ethereum-like smart contracts and benefit from the features, scalability, decentralization, and security of Initium.

A critical difference between Initium and other decentralized networks is the consensus protocol. Over time, people have come to a false understanding that blockchains have to be slow and not scalable. The Initium protocol employs a novel approach to the consensus to achieve its strong safety guarantees, quick finality, and high throughput without compromising decentralization.

$INIX is the native token of the Initium blockchain. It’s a hard-capped, scarce asset to pay for fees, secure the platform through staking, and provide a basic unit of account between the multiple Subnets created on Initium. Lepton is the smallest denomination of $INIX. One lepton is 0.000000000001 $INIX.

The rest of this paper is broken down into six major sections. Section 1 outlines the key properties of the Initium blockchain, its layers, subnets, technologies, and data structure. Section 2 outlines the innovative consensus of Initium, the Covenant, and its protocols that enable the entire blockchain's data integrity, scalability, and security. Section 3 outlines the architecture of the Initium blockchain networks and their interactions, bootstrapping, Sybil control and membership, and smart contracts. Section 4 outlines the Initium cluster and the role of nodes in the network. Section 5 discusses the governance model that enables dynamic changes to key economic parameters. Section 6 discusses various peripheral topics of interest, including potential optimizations, sharding, pruning, client types, post-quantum cryptography, and realistic adversaries.

The platform's name is Initium and is typically referred to as "the Initium platform" and is interchangeable/synonymous with "the Initium network" or "the Initium blockchain" or– simply– Initium. Codebases will be released using three numeric identifiers, labeled "v.\[0-9].\[0-9].\[0-100]", where the first number identifies major releases, the second number identifies minor releases, and the third number identifies patches.
