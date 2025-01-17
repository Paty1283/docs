---
description: Upcoming enhancements and updates to BlockScout
---

# Roadmap

{% hint style="info" %}
The Blockscout roadmap is a high-level strategic plan designed to guide research and development. **Target dates and details are reviewed regularly by the team and subject to move, adjust and change as the project evolves**. Note that only completed items ( :white\_check\_mark: Status: Complete) are considered achieved project milestones.

_Last update: July 27, 2022 |_ [_Changelog_](roadmap.md#change-log)__
{% endhint %}

## In Progress

### UI Redesign

**Target Date:** Q3-Q4 2021\
**Status**: :ballot\_box\_with\_check: In Progress

A new UI interface is under development to improve data exploration, optimize views, and provide overall better UX for Blockscout users. The UI is being built from the ground up. It will overhaul all aspects of Blockscout engagement, creating a complete all-in-one interface for chain exploration. In addition to a modern design, the upgrade will also improvements to features such as:

* **Search**:  Prominent search, mobile upgrades, improved dropdown, full-page results, search control
* **Data Sort/Filtering**: Ability to sort data (ascending & descending by column). Improved pagination and filtering abilities.
* **My Account**: See below for features related to My Account functionality.

### DApp Marketplace

**Target Date:** Q4 2021\
**Status**: :ballot\_box\_with\_check: In Progress

Chain users will be able to access applications and modules directly from Blockscout, vastly improving the overall chain experience. Interoperability, swaps, transactions, and 3rd party project-based apps will be accessible and integrated with the modular interface.

Blockscout will also develop native applications for this marketplace. Several are in active development.

* **Blockscout Swap**: Swap feature using an aggregator under the hood for simple swaps without leaving Blockscout.
* **Blockscout Revoke**: Find contracts/apps you have granted allowances to (the ability to spend tokens on your behalf) and revoke these permissions.
* More TBD

### My Account Functionality

**Target Date:** Q3 2022\
**Status**:  :ballot\_box\_with\_check: Instance deployed on Gnosis Chain. Undergoing improvements.

We will explore adding account features for users looking for explorer personalizations, including alerts and notifications, the ability to watch specific addresses, name and customize data within the dashboard, and other advanced features.

### Blockscout Rust Microservices

**Target Date:** Q3 2022\
**Status**:  :ballot\_box\_with\_check: In Progress

New Rust-developed microservices will be enabled on Blockscout to extend functionality and modularity. We are revamping smart contract verification to use a Rust module and working on a smart contract uml visualization module to start.

### Multi-Chain Search

**Target Date:** Q3-Q4 2022\
**Status**:  :ballot\_box\_with\_check: In Progress

Blockscout serves many different chains across the blockchain spectrum. Users currently must switch instances to find addresses/contracts etc for each chain. Multi-chain search will provide a single interface to track addresses across supported chains.&#x20;

### Landing Page

**Target Date:** Q3 2022\
**Status**: :ballot\_box\_with\_check: In Progress

A new landing page is in development for Blockscout to assist new users and developers understand the Blockscout feature set and find information quickly.

## Ongoing Improvements

### Data Storage Optimization

**Target Date:** **** :checkered\_flag:Ongoing

Updating and optimizing the indexing scheme for storable data. We are working to decrease the BlockScout database size while preserving the same level of functionality.

### Performance Enhancements

**Target Date:** :checkered\_flag:Ongoing - [80% covered in release 3.0.0](https://forum.poa.network/t/blockscout-v3-0-0-beta-block-hash-indexing-approach/3250)

As chain data grows exponentially, load speed, database optimization & caching, data parsing and front-end improvements are all required to maintain optimal performance. These efforts will continue as additional features are added to BlockScout.

## Research Phase - Future Items

### NFT  Interface

**Target Date:** 2023\
**Status**:🧪 Research Phase

As NFTs become more important to the ecosystem, the explorer will be updated and redesigned to display images, attributes and other data in a user-friendly interface. A dedicated NFT explorer module may be introduced to provide advanced features.

### Custom Transaction Views/Actions/Events&#x20;

**Target Date:** 2023\
**Status**:🧪 Research Phase

Create views for different actions / transactions to provide clarity for complex transactions, trade-specific transactions and multi-sig transactions.

### Personal Asset Management

**Target Date:** 2023\
**Status**:🧪 Research Phase

My Account functionality will be extended to enable portfolio views and management of assets across protocols and chains.

### Analytics Dashboards

**Target Date:** 2023\
**Status**: 🧪 Research Phase

We will incorporate new views and visual dashboards to better represent various data points.

### Blockscout ID

**Target Date:** 2023\
**Status**: 🧪 Research Phase

Develop an optional identification NFT to prove singular identity and increase utility across different apps on the platform (ie application-specific governance).

## Completed

### Deployment Improvements

**Target Date:** Q3 2022\
**Status**: :white\_check\_mark: Completed, Documentation in progress

BlockScout deployment can be complicated for new users. Deployment improvements within a Docker environment will enable a fast path for easy setup and deployment.

### Ethereum Mainnet BlockScout Instance

**Target Date:** Q2 2022\
**Status**: :white\_check\_mark: Instance deployed, optimizations ongoing.

BlockScout offered prior support for the Ethereum mainnet. This instance was discontinued;  however a new instance is now planned to further increase explorer diversity on Ethereum and provide additional transparency for Ethereum users.

### ERC721 Metadata

**Target Date:** Q4 2019\
**Status:** :white\_check\_mark: Complete, ERC721 Metadata storage and display ([Release 2.1.0](https://forum.poa.network/t/blockscout-2-1-0-release/3128)) and verification checks ([Release 2.1.1](https://forum.poa.network/t/blockscout-2-1-1-release/3172)) are implemented.

[ERC-721](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-721.md) non-fungible tokens represent ownership of digital or physical assets. Each token is unique, and may include images and other data which identifies the asset and provides additional information. This might include registration information (for example land, property or art registration), identifying numbers or other data unique to that token. As ERC-721 tokens continue to proliferate, it is important to display the relevant information related to each owned token.&#x20;

### Staking DApp Integration

**Target Date:** Q3 2020\
**Status:** :white\_check\_mark: Complete Q4 2020

BlockScout will support the new POSDAO staking consensus mechanism through an on-board UI. The initial implementation will support the [xDai Stable Chain](https://xdaichain.com). This will allow users to place stake directly from the interface, monitor validator activity, and participate in consensus on the xDai Chain.

### Smart Contract Write Functionality

**Target Date:** Q2 - Q3 2020\
**Status**: :white\_check\_mark: Complete, Write contract/ write proxy functionalities are implemented ([Release 3.3.0](https://forum.poa.network/t/blockscout-v3-3-0-beta/3558)).

Users can currently verify and read contracts on BlockScout. The next smart contract development phase will allow users to interact with contracts directly through the interface.  Verified contract methods will be accessible and users can connect through a web3 wallet (such as MetaMask) to access and execute contract functions.

### ERC1155 Support

**Target Date:** Q2 2021\
**Status**: :white\_check\_mark: Basic Functionality added for xDai chain, additional support in process.

ERC-1155 tokens are increasing in popularity as a way to manage multiple-token types including fungible and non-fungible tokens within a single instance. This feature provides parsing and display of tokens contained within an ERC-1155. Additional functionality such as metadata display is in process.

### Rollup Support

**Target Date:** Q4 2021\
**Status**: :white\_check\_mark: Instances for Optimism and Arbitrum on Gnosis Chain

BlockScout availability and support is available for Optimism and Arbitrum on the Gnosis Chain. Includes tracking for gas price on L1 and the L2 implementations. Currently Optimism is the favored deployment.

* Optimism: [https://blockscout.com/xdai/optimism](https://blockscout.com/xdai/optimism)
* Arbitrum: [https://blockscout.com/xdai/aox/](https://blockscout.com/xdai/aox/)

### EIP-1559 Support

**Target Date:** Q3-Q4 2021\
**Status**: :white\_check\_mark: Complete

The Gnosis Chain explorer supports EIP-1559 functionality with a stated transaction type (2 for EIP-1559) and includes data reporting of Max Fee per Gas, Max Priority Fee per Gas and Priority Fee / Tip paid for a transaction.

### Multi-file Contract Source Code Verification

**Target Date:** Q4 2021\
**Status:**  :white\_check\_mark: Complete

BlockScout supports verification for contracts via multiple methods including Hardhat and the Hardhat and Sourcify plugins. [More information is available here](../for-users/smart-contract-interaction/verifying-a-smart-contract/).

## Change Log

| Update       | Items                                                                                                                                                                                                                                                                                                                                                                                            |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 27.07.2022   | <ul><li>Updated marketplace to include Blockscout native DApps</li><li>Added Blockscout Microservices</li><li>Added Multi-chain search</li><li>Added personal asset management features</li><li>Added Blockscout ID</li><li>Combined several elements into UI category</li><li>Deployment improvements (Docker image) moved to completed.</li><li>Update Research Phase items to 2023.</li></ul> |
| 06.07.2022   | <p>Added:</p><ul><li>Analytics Dashboards</li><li>UI Overhaul</li><li>Modular Plug-and-Play Library</li></ul><p>Completed:</p><ul><li>Ethereum Mainnet Instance<br></li></ul>                                                                                                                                                                                                                    |
| 11.04.2022   | <ul><li>Rearranged into Completed and Ongoing Categories. </li><li>Updated Ongoing Item dates</li><li>Added UI enhancements</li><li><p>Marked as Completed</p><ul><li>EIP-1559 Support &#x3C;Completed></li><li>Rollup Support &#x3C;Completed></li><li>Multi-file Contract Source Code Verification &#x3C;Completed></li></ul></li></ul>                                                        |
| _04.08.2021_ | <p></p><ul><li><p>Added multiple new items to Q4 Roadmap including:</p><ul><li>EIP-1559 Support</li><li>Ethereum Mainnet Instance</li><li>My Account Functionality</li><li>Rollup Support</li><li>Deployment Improvements</li><li>Multi-file Contract Source Code Verification</li><li>Block/Address Detail Page Improvements</li><li>Data Sorting/Filtering</li></ul></li></ul>                 |
