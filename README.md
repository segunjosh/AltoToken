# Altostream Technical WhitePaper V1.0. 

# Date: 02 July 2020

# Abstract

Artist, music producers and song writers have worked relentlessly over the years to provide appreciable music; their listeners spend huge amount of time and resources to support their favorite artist. At the same time, giant platforms profit from those endeavours and have grown into famous multi-billion dollar labels and corporations from less known recording studios.

### Table of Content

- [Introduction](#introduction)
  - [Censorship](#censorship)
  - [Ownership](#ownership)
  - [Immutability](#immutability)
  - [Governance](#governance)
  - [Economic Incentives](#economic-incentives)
  - [Execution Environment](#execution-environment)
- [Bitcoin](#bitcoin)
  - [Introduction](#introduction)
  - [Consensus Mechanism](#consensus-mechanism)
  - [Low Transaction Throughput](#low-transaction-throughput)
  - [Alternative Consensus Mechanisms](#alternative-consensus-mechanisms)
  - [Alternative Consensus Mechanisms](#alternative-consensus-mechanisms)
- [Introducing Bitcoin-NG](#introducing-bitcoin-ng)
  - [Altostream Protocol](#Altostream-protocol)
  - [Consensus Model](#consensus-model)
  - [Hybrid Protocol](#hybrid-protocol)
  - [Bitcoin-NG — Leader-based Block Creation](#bitcoin-ng--leader-based-block-creation)
  - [Coin](#coin)
- [The Value-based content Economy is designed on three fundamental principles](#the-value-based-content-economy-is-designed-on-three-fundamental-principles)
  - [No platform cuts](#no-platform-cuts)
  - [Rewards Incentives](#reward-incentives)
  - [Decentralized Ownership](#decentralized-ownership)
- [Altostream Blockchain Overview](#Altostream-blockchain-overview) 
- [Altostream COIN](#Altostream-coin)
  - [Musicians](#1-musicians)
  - [Users](#2-users)
  - [App Developers](#3-app-developers)
  - [nfrastructure Providers Infrastructure providers provide storage](#4-infrastructure-providers-infrastructure-providers-provide-storage)
  - [Validators](#5-validators)
- [Conclusion](#6-conclusion)
- [References](#7-references)

### Introduction

The vast majority of musicians, producers and song writers have not benefited or have been cheated out of the financial gains of the businesses they helped to build but also have been forced to accept the disproportionate revenue sharing rules established by those platforms (typically, current platforms take a 30-50% cut from artists earnings). 
In Addition, higher monetization bars and unfair content promotion further threaten the survival of many in the music industry.

Giant platforms' exploitation of musicians worsens by the day due to the fundamental conflict of interests between musicians and platforms owned by corporations.

Corporations' fundamental interests are to maximize their own profits, they do not share the profits with artistes and fan base. Leveraging on blockchain technology, Altostream aims to revolutionize the content sharing industry.

### Censorship
“Code” is free speech; similar to human languages, it is a form of expression used to communicate ideas; This has been proven in a U.S court [4] in the case between Bernstein v. the United States where Bernstein wanted to publish a paper and source code of his encryption system [5]. However, the government required him to submit his ideas for review and register to acquire a license as an arms dealer, and failure to do so would result in criminal penalties. Bernstein sued the government and won when it was ruled that the First Amendment protected software source code. However, not many countries have laws that recognise code as free speech. As a result, code sharing platforms are exposed to request and demands from governments to censor projects created by individuals of interests. It is not news that Github continues to face threats and attacks from governments[6] who want repositories removed. While code sharing platforms face a real threat from external and hostile actors, these services themselves can also exert censorship actions upon users and their projects according to predetermined or arbitrary terms which are mostly driven by their business models. Additionally, not only are users exposed to censorship behaviours incited by external agents and the code sharing platform, but they are also vulnerable to censorship by project admins or maintainers. Project maintainers are free to cut access to a repository they manage at any time and on their terms.
The various levels of censorship threats make centralised code sharing platform unsuitable for hosting communities building innovative, competitive and possibly contentious applications and services. As long as contributions are hosted centrally, repositories continue to remain under potential threat.

### Ownership
Most tools and services on the internet support a single owner account architecture. An architecture that recognises and grants ownership and authority to one person identified by their email or phone number. Some of the motivation for this is the need to maintain security and to determine who pays the bills. Code sharing platforms are among these service providers built on this single-owner structure. All repositories must be owned and managed by one person who is granted full privileges to create, access, add members and destroy any resource associated with their account without notice.
The consequence of this is that complicated, sovereign and community-led organisations cannot build software in a trust-less manner since these collaborators must trust the root account owner. One approach employed to remedy this problem involves the creation of committees and other secondary structures. However, we argue that these structures do not deliver real ownership and governance since there is a root password managed by an individual or organisation. In the crypto industry, they say “If you do not own your private keys, you do not own the coins”. Likewise for open source projects on a code sharing platform, “If you do not own the password, you do not own the project”. It is essential that contributors to community-led platforms can honestly and provably share ownership of a project without needing to trust a central authority such as the owner or maintainer of a repository or the platform operator. Real ownership of a community-owned software cannot be granted based on faith that the authority will always act in the best interest of collaborators.

### Immutability
The concept of immutability in computing refers to the unchanging, unalterable state of data. It refers to the inability of a piece of data to be altered. Immutable data is easy to reason about; We can make assumptions and build on top of them with certainty that their state will not change unexpectedly. Interestingly, the Git version control system used by millions of collaborators and supported by most code sharing platforms utilises an immutable data structure. Git includes concepts like branches and commits; Commits are backwards-linked collections of changes that exist inside a branch. Collaborators can begin working from any commit and never have to worry that future commits may alter the state of the commits they are extending. However, code sharing platforms do not guarantee immutability of an entire repository. Repositories as a whole are not immutable; Their owners or the platform operators can delete them. It is important to note that the ability to delete repository can serve as a tool for censorship. An account owner or platform operator can prevent people from collaborating by removing a repository from existence. Although repositories can be cloned easily, it is more challenging to re-organise a community disrupted by an act of censorship. The lack of guaranteed immutability on code sharing websites makes them unappealing for hosting community-led services. It will be devastating for a community to one day find their shared enterprise deleted by the account owner or platform operator.

### Governance
For open source communities to succeed in creating and managing decentralised organisations, they must first figure out governance, otherwise what would be obtainable is chaos, uncertainty, indecision, and unaccountability. These communities need to be able to formulate a governance system that is acceptable to all parties and enables them to make decisions quickly and fairly. On centralised code sharing platforms, there is only one kind of governance system — One where the account owner dictates how and when collaborators interact with and contribute to the project. As a remedy, big projects delegate control to reputable, structured open-source organisations like Apache Software Foundation or the Linux Foundation. The ideal collaboration framework for decentralised organisations must take a vendor-neutral stance, only providing primitives and templates that can be used or adapted to create simple to complex governance models with enforcement carried out by the protocol where possible.

### Economic Incentives
People do not contribute to open source software irrationally. They do it because there is something to gain. Many people contribute because they want to learn or be members of a community of like-minded individuals. There are those who do it to improve their reputation so that prospective employers may be interested in their abilities. Companies whose business model depends on open source software are also incentivised to contribute to it.

A popular misconception about open source is the idea that open source contributions should attract no financial incentive and remain a free and voluntary activity. However, the truth is, most open source contributions impose time and financial commitments on contributors who need to develop, test, document, evangelise the product and fix bugs to ensure the product is suitable for both individual developers and enterprises. It is unrealistic to expect contributors to consistently offer their time and money to a project that gets used by others for commercial purposes and to expect no form of financial compensation as incentives to continue to remain committed to the long term improvement and sustenance of the project. If the quality of open source software is to be maintained or improved, the best way to guarantee it is by bringing financial incentives to the table.

Two of the main channels from which open source collaboration may receive financial support are code-sharing platforms or open source foundations. Code sharing platforms can create mechanisms that could potentially allow open source developers to receive financial assistance in the form of donations or subscription to premium branches, but they do not do this. These platforms do a lot to enable collaboration but not enough to allow contributors to receive financial benefits.

Open source foundations such as Apache Software Foundation can receive donations and generate income through sponsorship, merchandise sales, support and hosting conferences but those funds are for the day-to-day running of the foundation of which none of it goes down to non-employee contributors. There needs to be a trusted, transparent and automated mechanism for creating, verifying and transferring value between users and collaborators of open source software. The introduction of such a mechanism will create many types of open source economies (such as bounty, bug hunting, support services).

In the era of community-led services, collaborators need to be able to generate or receive financial rewards to support continuous development and execution of their services. While centralised code sharing platforms are unsuitable for providing the needed infrastructure, blockchain technology can allow collaborators create shared software products, formulate protocol enforceable governance structure, vote and authorise actions, receive and distribute financial incentives without intermediaries.

### Execution Environment
To go beyond projects like libraries, frameworks, CLI tools to community-led services, we need to begin to consider program execution environments that are suitable for running shared applications in the form of dApp, SaaS, API and other types of software. This execution model must lend itself to be deployed, operated and governed according to the governance structure instituted by the community.

Collaborators will need an environment to run tests, stage and deploy their applications. Most code sharing platforms only provide continuous integration environments with the configuration of this environment still subjected to the authorisation of the single-user account owner. There is a need for a mechanism that allows a community to collectively decide what kind of execution environment and configuration they want for their projects.

A deployment environment includes a tool that runs an application and makes it accessible to target users. The ideal deployment environment must be unalterable, autonomous and can only allow itself to be upgraded according to the governance rules of the community.

Historically, consumer applications have been executed in a centralised, managed environment but with the emerALTOe of blockchain platforms like Ethereum, applications can now be executed decentrally on thousands of nodes in a trust-less and autonomous manner. Decentralised applications are immutable; they cannot be altered or destroyed once deployed.

While many believe blockchain applications should replace all centralised applications, we believe community-led services can leverage both types of execution environments depending on their goals; This way they are better positioned to compete with centralised services providers on all fronts.

Collaborators may decide to build completely decentralized application that cannot be altered once deployed if the nature of their value proposition demands it. Otherwise, they may simply create centrally executed applications like SaaS, API, mobile application and more. These communities building centralised applications can setup governance system that is strong enough to provide some of the qualities of decentralized applications (immutability, openness, transparent and autonomy) through enforcement of an open and transparent constitution.

The ability to build applications that can leverage the best of decentralisation and centralisation will help collaborators build useful applications that can easily gain adoption and deliver great value and experience to users.

### The Ideal Platform for Open Source Service
In section 2, we discussed the reasons why centralised code sharing platforms are unsuitable to lead the change towards a future of community-led software products and businesses. These changes range from censorship, ownership, and governance to execution models. We can see that the major obstacle is the inability to enforce ownership, transparency and accountability.

**We take the following approaches to solve the issues:**

1. Altostream will use blockchain technology to eliminate censorship concerns by creating a new type of decentralised collaboration framework that is open to anyone, anywhere and cannot be destroyed. There will be no entity to receive and carry out censorship requests.

2. The use of public key cryptography as the primary mechanism to create identity and to authorise actions, will allow projects to have multiple owners or signatories who can partake in the day-to-day governance of the project.

3. By the very nature of blockchains, repositories will remain immutable: They will always be accessible to everyone. Although, owners of the repositories may enable the ability to apply access level rules to prevent unauthorised write operations.

4. The introduction of autonomous procedures (a.k.a smart contracts) will allow communities to create immutable applications to enforce ownership, governance, incentive structure and disbursement and business rules. Many nodes on a blockchain network execute autonomous procedures in a way that ensures correctness and resilience to attacks that would normally cripple a centralised equivalent.

5. The use of Git makes it easy for millions of developers who are already familiar with the tool to easily create repositories, contribute, import their existing projects and integrate with other git compatible tools and services they already use.

6. The combination of public key cryptography and the ability to create complex governance structures, external service providers can deliver value based on the governance history or events (e.g. proposals) of a project. For instance, a community may create and vote for a proposal to run ads on Google Adwords, upon the approval, a designated service creates a campaign on Google Adwords using the information provided in the proposal.

### Bitcoin
In this section, we would briefly discuss about bitcoin, its consensus mechanism and particularly its inability to process enough transactions per second to meet mainstream users’ needs.

### Introduction
Bitcoin is a form of electronic cash. It is a decentralised digital currency that does not have a central bank or a trusted authority. It can be sent from person-to-person faster and cheaper without restrictions. With cryptography, transactions are verified and transmitted through a peer-to-peer network of computers that update account balances and record changes in a public distributed ledger known as a blockchain. Bitcoin was invented by Satoshi Nakamoto[8] and released to the public as an open source software in 2009.

### Consensus Mechanism
Blockchain networks require a means to reach an agreement on a single value. Consensus algorithms define the rules that must be followed by computers on the network in other to reach an agreement. The process of agreeing with other computers is known as the consensus problem, and it is a well-researched field in computer science. Bitcoin uses a consensus algorithm known as Proof of Work9. It is used to process blocks of transactions and append them to a chain of blocks — the blockchain. In Bitcoin, the process of appending a block to the blockchain is known as “mining”, and the individuals who take part in the mining process are known as “miners”. PoW requires miners to solve complex cryptographic puzzles to gain the right to add a block.

Miners receive newly created Bitcoin as a reward for solving the puzzle. This reward is known as the block reward. Before the reward is issued, the generated block must follow the consensus rules. All other nodes on the network are responsible for verifying the block and enforcing the consensus rules. Once a miner discovers a valid block they did not create, they immediately stop and start mining the next block. There is a network difficulty that ensures that blocks are created within 10 minutes. It determines how hard it is for the miners to mine a block and is adjusted dynamically to maintain the 10 minutes window.

Bitcoin’s PoW has a disadvantage of being very slow. It has been described as a consensus system that wastes energy and is causing harm to the planet. However, it is the most battle- tested and well understood trustless consensus system in the cryptocurrency industry.

### Low Transaction Throughput
Bitcoin pioneered the blockchain industry and made it attractive for different categories of people who believed in its vision. Developers have created clones and alternative implementations intending to improve on the capabilities of Bitcoin. One of the primary motivation fueling the creation of Bitcoin alternatives is the inability of the Bitcoin network to process large amounts of transactions sufficient to handle the needs of mainstream users. It takes 10 minutes for the bitcoin network to create a new block and even more to attain minimum confirmation of a transactions finality. Most people agree that for cryptocurrency to go mainstream and be capable of competing centralised incumbent, blockchains must be able to handle thousands of transaction per second.

### Alternative Consensus Mechanisms
Since the introduction of Bitcoin, developers and researches have been working on alternative consensus algorithms that are more efficient and performant than proof-of-work. The most popular of these alternatives is Proof of Stake (PoS).
In Proof-of-Stake consensus, the blocks are not created by miners solving computationally hard math puzzles, but by participants who stake their money to bet on the validity of a block. These participants take on the role of block forgers and validators. Proof of Stake is a faster and more energy efficient alternative to Proof of Work, but it suffers from a severe problem known as “Nothing at Stake”. The concern behind “Nothing at Stake” is that since it cost next to nothing to create blocks that support a fork, validators can vote for every fork that happens without any severe consequence; This is unlike proof-of-work where a computationally hard problem must be solved to extend the main branch or a forked branch. Modern PoS systems employ a strategy that punishes misbehaving participants who failed to follow the consensus rules by slashing their stake.

### Introducing Bitcoin-NG
The performance of blockchain protocols is limited by two factors — block size and block interval. Increasing the block size correlates to an increase in transaction throughput. However, bigger blocks take more time to propagate to nodes on the network and can lead to an increase in forks if these blocks arrive late. Decreasing the block size reduces the time it takes for blocks to propagate to nodes, but doing so rapidly leads to forks and frequent reorganisation. The Bitcoin system traded transaction throughput for latency by using a small block of 1MB with a 10 minutes block time: Blocks are sufficiently propagated throughout the network due to the block time, but minimal transactions are processed.

Bitcoin-NG is a scalable blockchain protocol designed to improve the throughput of Bitcoin without affecting the same trust model that exists in Bitcoin. It achieves performance improvement by introducing the concept of a leader election and transaction serialisation. In Bitcoin-NG, time is divided into periods known as “epoch” where every epoch has a leader. Once a node becomes a leader, it is expected to produce blocks until a new leader is discovered. Leader election is performed randomly in the same way miners in Bitcoin find blocks infrequently. Bitcoin-NG ensures that the system can process transactions even when the network works to find a new leader unlike Nakamoto Consensus in Bitcoin where no transaction is processed during the 10 minutes block interval.

### 5. Altostream Protocol

In this section, we would describe the engineering direction of our protocol. Having a knowledge of blockchain technology is essential. Please note that some concepts described below are not final and may be subject to change as we continue to execute our vision.

### Consensus Model

### Hybrid Protocol

The Altostream consensus mechanism is a hybrid consensus algorithm of both Proof-of-Work and Proof-of-Stake. Our consensus model is based on concepts described in the Proof of Activity[11] protocol by Iddo Bentov et al. They described a process of extending Nakamoto Proof of Work via Proof of Stake to increase the security of the network while reducing the dependence on miners as the only contributor to network security. Iddo Bentov et al. questioned the capability of Bitcoin miners to sustain the security of the system when PoW is no longer subsidised via the block reward. We agree with their assertion that a cryptocurrency protocol should be designed in such a way that its incentive structure encourages different participants in the system to sustain its health.

### Bitcoin-NG — Leader-based Block Creation

Bitcoin-NG extends Nakamoto consensus into a protocol that is capable of processing more transactions than Bitcoin. It does this by introducing a leader-based block creation scheme where a miner is entitled to create several more blocks at faster intervals after they mined a block known as a “key block”. Ellcrys PoW implementation is based on Bitcoin-NG to improve transaction throughput through improved latency and bandwidth.

### Coin

In most public blockchain systems with a native cryptocurrency, new coins are generated when a new block is mined. The generated coins are shared to the miner and any other network participants who contributed to the creation or validation of the new block at a predetermined ratio. In Bitcoin and other similar proof-of-work blockchains, the miner of the block receives all newly generated coins.

We believe a system built on a coin generation model where a single participant receives all rewards is unfair and does not promote equitable distribution of wealth generated by the network. Centralization of rewards within a wealthy minority further replicates and increases the existing gap between the rich and poor. In matured proof-of-work blockchains like Bitcoin, a user needs specialised equipments to compete with well-funded corporate organisations. Although, one might argue that these networks provide security to the network, but they may also become future adversaries when incentives falling below their cost of operation due to low block rewards.


### The Value-based content Economy is designed on three fundamental principles.
- **1. No platform cuts:** 
To fully motivate content creators, key persons in maintaining the long- term growth of music streaming platforms. Apps utilizing the Altostream blockchain would not take any cuts from direct payments between listeners and musicians. In the user-generated content sharing industry, long-term growth cannot be maintained unless the majority of the profits go back to its creators as these will enable them to produce more quality content.
- **2. Reward incentives:** 
To further motivate all contributors and users to keep the applications sustainable on a long run. The Altostream blockchain is designed to record and reward all its contributors as key stakeholders. These includes app developers, infrastructure providers, validators, musicians and listeners whose contributions which are crucial to achieving a long- term sustainability
- **3. Decentralized Ownership:** 
To distribute the network value back to all contributors and prevent centralized decision making that compromises contributors' interests for the benefit of a small group of stakeholders. The Altostream blockchain is designed to allow network ownership and value be distributed among its contributors and as these factors exist, it becomes more decentralized over time. We've seen current centralized music streaming platforms make arbitrary decisions that do not favour musicians: higher cuts and stricter monetization rules. 

*The decentralized Altostream blockchain aims to achieve a balanced system to favour all its contributors, and to ensure every decision aligns with all parties’ interest.

### Altostream Blockchain Overview
The Altostream blockchain contains unique identifiers for contributors, infrastructure providers, App developers and validators, and listeners, allowing any music content platform adopting the same usage to properly identify and record contributions made by each stakeholder.

### Altostream COIN:
AltoToken is the fundamental unit of value on the Altostream blockchain it's symbol is ALTO. The Altostream blockchain is designed to algorithmically reward all contributors with new nodes of AltoToken that is produced per block. 50% of AltoToken goes to the newly installed nodes by infrastructure providers; 15% goes to App developers; 15% goes to Validators 20% goes to musicians; and the remaining 10% goes to listeners. 

The total supply in AltoToken will not exceed 25 Million, It is divisible to 18 decimal places. Its official Unicode character is ȅ (U+0205). At the launch of the main network, the initial supply cannot exceed a total of 25,000,000.

This system is designed to ensure that App developers, infrastructure providers, validators, musicians, and listeners are fully compensated for their contributions to achieve a long-term sustainability.

## 1. Musicians:
Musicians produce and publish original songs, mix-tapes and albums. They are the most critical contributors to any music streaming platform, and the Altostream blockchain is designed to fully incentivize them to continuously produce high-quality music and sound tracks, keeping the whole system robust in the long term. 90% of all donations and paid subscriptions made using Altostream blockchain will be paid algorithmically to musicians and the remaining 10% will be held in reserve by the blockchain protocol and distributed to all Altostream COIN Stake (See illustration below) holders as Voting Rewards for their contribution to the blockchain governance. 

Apps utilizing the Altostream blockchain protocol should not take cuts from donations, paid subscriptions, and any other transactions between musicians and listeners. In addition, musicians will receive song rewards in Altostream COIN based on the performance of their song. An algorithm called Proof of Song Value is built into the Altostream blockchain to allocate Song rewards fairly and prevent bots from abusing the system. A musician can also receive income from Altostream Voting Rewards.

## 2. Users:
Users spend a huge amount of time and money to support content creators, yet receive nothing for their contribution. The Altostream blockchain will distribute listeners Rewards algorithmically to incentivize actively engaged users. In the future, the reward distribution algorithm will evaluate a viewer's watching time, chat frequency, and donation behaviours to fairly allocate the reward.

## 3. App Developers:
App developers can build apps using the infrastructure provided by the Altostream blockchain for content creators and viewers. In order to be an App developer, a user must stake a certain number of Altostream.

# 4. Infrastructure Providers Infrastructure providers provide storage:
Content Delivery Network (CDN), and transcoding services for the Altostream Apps. They are rewarded through Infrastructure Rewards and LS Voting Rewards. In order to be an infrastructure provider, a user must stake a certain number of Altostream COINS.

# 5. Validators:
Validators produce blocks and validate transactions on the blockchain and receive transaction fees in return. They are also rewarded by Block Rewards/Validation Rewards and LS Voting Rewards. In order to be a validator, a user must stake a certain number of Altostream.


### Conclusion

Altostream's mission is to facilitate a Value-based content Economy where musicians and all other contributors are fully incentivized to maximize long-term economic growth in a sustainable way.

### References
- Bitcoin - https://bitcoin.org/bitcoin.pdf
- Git - https://en.wikipedia.org/wiki/Git
- Github - https://github.com
- Bernstein vs. United States - https://en.wikipedia.org/wiki/Bernstein_v._United_States
- Snuffle - https://cr.yp.to/snuffle.html
- Censorship of Github - https://en.wikipedia.org/wiki/Censorship_of_GitHub
- Blockchain - https://en.wikipedia.org/wiki/Blockchain
- Satoshi Nakamoto - https://en.wikipedia.org/wiki/Satoshi_Nakamoto
- Proof of Work - https://en.bitcoin.it/wiki/Proof_of_work
- Bitcoin-NG: A Scalable Blockchain Protocol - https://arxiv.org/abs/1510.02037
- Proof of Activity: Extending Bitcoin’s Proof of Work via Proof of Stake - https://eprint.iacr.org/2014/452.pdf
- Hyperledger Fabric: A Distributed Operating System for Permissioned Blockchains - https://arxiv.org/pdf/1801.10228.pdf
- Git Hooks - https://git-scm.com/docs/githooks
- Aragon Court - https://forum.aragon.org/t/aragon-court-v1/691
- On Consensus and Humming in the IETF - https://tools.ietf.org/html/rfc7282


