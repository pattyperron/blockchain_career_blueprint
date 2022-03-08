[**Home**](home.md)

[**Prev: Blockchain Careers**](blockchain_careers.md)

----
![](https://www.sap.com/dam/application/imagelibrary/photos/287000/287437.jpg/_jcr_content/renditions/287437_homepage_3840_1200.jpg.adapt.1920_522.true.false.false.false.jpg/1629157434919.jpg)

# Blockchain Concepts
The following section describes concepts that are common across the blockchain ecosystem and that the creators of this guide believe are important to be aware of when entering this space. While only a high-level understanding is recommended to get started, each concept has links to resources that can be consulted if the user believes a deeper understanding is needed.

### Bitcoin
Bitcoin is the blockchain-based cryptocurrency and the first real-world application of blockchain technology. It was proposed by a pseudonymous founder, Satoshi Nakamoto, in a [2008 white paper](https://bitcoin.org/bitcoin.pdf) that first introduced blockchain technology to the world. There are no physical currency tokens in Bitcoin, "only balances kept on a public ledger that everyone has transparent access to (although each record is encrypted)" ([Frankenfield, 2021a](https://www.investopedia.com/terms/b/bitcoin.asp)). Rather than accounts associated with individuals or corporations, the ownership of Bitcoins is associated with [public keys](https://www.investopedia.com/terms/p/public-key.asp) visible to the whole network and use [private keys](https://www.investopedia.com/terms/p/private-key.asp) to authorize transactions.

In contrast to [fiat currency](https://www.investopedia.com/terms/f/fiatmoney.asp) like the US dollar, the supply of Bitcoin cannot be controlled by any individual or organization. Bitcoins are created through [bitcoin mining](https://www.investopedia.com/terms/b/bitcoin-mining.asp) using a system called [proof of work](https://www.investopedia.com/terms/p/proof-work.asp). In this system, nodes on the Bitcoin network attempt to solve a mathematical puzzle before other nodes in the network can, and the first to solve the puzzle gets to create the next block in the blockchain and will be awarded bitcoin that did not previously exist. To control the diffusion of supply, Bitcoin is designed to halve the reward for mining new blocks at 210k blocks (approximately every 4 years). The planned supply limit built into bitcoin is 21 million, which will occur around 2140. As the price of bitcoin has risen, bitcoin mining has become more lucrative but also more competitive. The energy requirements for this process have also created environmental concerns that have caused newer cryptocurrencies to seek proof of work alternatives like [proof of stake](https://www.investopedia.com/terms/p/proof-stake-pos.asp).

### Ethereum
Ethereum is a blockchain-enabled platform proposed in a [2014 white paper](https://ethereum.org/en/whitepaper/). While it's also known for its cryptocurrency by the same name, Ethereum is unique in that it's the first platform to support the creation of user-made [decentralized applications(dApps)](https://ethereum.org/en/developers/docs/dapps/) that make use of smart contracts (see Smart Contracts section).

Ethereum positions itself as ["the world's programmable blockchain"](https://ethereum.org/en/what-is-ethereum/) and serves as one of the key platforms to enable blockchain-based technologies like Distributed Autonomous Organizations (DAOs) and Non-fungible Tokens(NFTs). The Ethereum network is also the foundation for many different types of tokens built, and it has produced various standard formats for tokens([ERC-20](https://www.investopedia.com/tech/why-crypto-users-need-know-about-erc20-token-standard/)) or NFTs([ERC-721](https://ethereum.org/en/developers/docs/standards/tokens/erc-721/)) that developers can use if they want the dApps to interface properly with other assets stored in the Ethereum network.

Ethereum's programmability allows it to serve as a foundation for a vast array of applications that could never work with Bitcoin, but this flexibility comes at a cost of security risks. In a famous [hack](https://www.gemini.com/cryptopedia/the-dao-hack-makerdao), a vulnerability in Ethereum's smart contract language, Solidity, resulted in $50 million worth of Ethereum being stolen. Since smart contracts are written to the Ethereum blockchain, errors within them are irreversible.

There are now many blockchain solutions following Ethereum that support the creation of smart contracts and decentralized applications, but as of 2022 Ethereum is still one of the most popular.

### Smart Contract

Smart contracts are a key part of the value proposition provided by blockchain technology. They are "programs stored on a blockchain that run when predetermined conditions are met. They typically are used to automate the execution of an agreement so that all participants can be immediately certain of the outcome, without any intermediary’s involvement or time loss. They can also automate a workflow, triggering the next action when conditions are met" ([Smart Contracts Defined, 2022](https://www.ibm.com/topics/smart-contracts)). 

Ethereum was the first blockchain platform to support smart contracts, but many blockchains like Solana, Hyperledger Fabric, and Polkadot have since been developed. Like other computer programs, there are standardized languages like [Solidity](https://soliditylang.org/) (for Ethereum) and [Chaincode](https://hyperledger-fabric.readthedocs.io/en/v1.0.0-beta/chaincode.html) (for Hyperledger Fabric), but various blockchains are developing their own conventions for writing smart contracts.

Security is a critical issue in smart contracts because these programs can manage large sums of value and transactions cannot be reversed if there are bugs in the program. A common solution for companies deploying smart contracts is to hire an external [auditing firm](https://www.gemini.com/cryptopedia/smart-contract-audit-crypto-hack) to their contracts before deployment. There is also research on using [formal methods](https://dl.acm.org/doi/pdf/10.1145/2993600.2993611) for smart contract verification.

### Cryptocurrency

A cryptocurrency is a digital form of currency implemented on a specific instance of a blockchain. Bitcoin was the first cryptocurrency, but there are now several versions of bitcoin (Bitcoin(BTC), Bitcoin Satoshi's Vision (BSV), Bitcoin Cash (BCH)) that were created when different design philosophies caused the currency to [fork](https://www.coinbase.com/learn/crypto-basics/what-is-a-fork). A cryptocurrency can interface directly with smart contracts, which give these applications the ability to automatically transfer the ownership of tokens to different parties without relying on a third-party intermediary. 

Typically, users "store" their cryptocurrency in a [cryptocurrency wallet](https://www.coinbase.com/learn/crypto-basics/what-is-a-crypto-wallet), which is a computer program (e.g. [Metamask](https://decrypt.co/resources/metamask)) or physical device (e.g. [Ledger](https://www.ledger.com/)) designed to securely store the private keys to a user's cryptocurrency (but not the currency itself, which is stored on the blockchain).

### Hyperledger

[Hyperledger](https://www.hyperledger.org/) is a consortium of open-source blockchain projects directly supported by the Hyperledger Foundation, which itself is part of the Linux Foundation. Hyperledger includes various projects including a permissioned blockchain solution (Hyperledger Fabric), a collection of libraries for digital identity management (Hyperledger Indy), and a toolkit for managing credentials(Hyperledger Aries). The Hyperledger Foundation also provides [certifications and training](https://www.hyperledger.org/learn/training) to help developers get involved. Hyperledger provides an extensive toolkit to any practitionner wishing to develop an enterprise-grade blockchain solution.
S
### Distributed Ledger Technology (DLT)
Distributed Ledger Technology is an umbrella term for "technological infrastructure and protocols that allows simultaneous access, validation, and record updating in an immutable manner across a network that's spread across multiple entities or locations."([Difference Blockchain and DLT, 2018](https://marcopolonetwork.com/articles/distributed-ledger-technology)) Though often used interchangeably, Blockchain is just one implementation of DLT.

### Public/Private Blockchains

While data stored in a blockchain is distributed and immutable, its accessibility is dependent on the characteristics and configuration of the system. A [permissionless(private) blockchain](https://www.investopedia.com/news/public-private-permissioned-blockchains-compared/) is one where all data stored within it is publically accessible. An example of such a blockchain is Bitcoin, where the amounts of bitcoin associated with each public key are accessible to everyone. While Bitcoin does not store the names of the individuals or organizations associated with each address, nothing is stopping an individual from figuring out how much Bitcoin someone owns if they know their public key.

By contrast, a permissioned/public blockchain is one where only certain participants are allowed to access the stored information. This configuration is useful when the blockchain is being used to store confidential information but needs to guarantee immutability. Hyperledger Fabric is an example of a popular permissioned blockchain.

Practitioners should understand the requirements of their proposed blockchain solution to best decide whether a public or private blockchain is best.

### Oracles

Smart contracts need access to reliable information if they are to behave properly. Oracles are "third-party services that provide smart contracts with external information" that "serve as bridges between blockchains and the outside world" ([Blockchain Oracles Explained, 2022](https://academy.binance.com/en/articles/blockchain-oracles-explained)).

The most common kind of oracles is an [input oracle](https://chain.link/education/blockchain-oracles), which feeds external input into the blockchain from various types of data, such as the weather, a user's credit score, or the readings from specific sensors. There are also [output oracles](https://chain.link/education/blockchain-oracles), which feed the results of smart contracts off of the blockchain to external systems, and [cross-chain oracles](https://chain.link/education/blockchain-oracles), which allow data to be securely exchanged across different blockchains.

Oracles play an important role in any blockchain system that needs to securely interface with outside components.


### Distributed Autonomous Organization (DAO)

A distributed autonomous organization is a new form of an organization or entity where "the
management and operational rules are typically encoded on blockchain in the form of smart contracts, and can autonomously operate without centralized control or third-party intervention" ([Wang et al., 2019b](https://www.researchgate.net/publication/335800811_Decentralized_Autonomous_Organizations_Concept_Model_and_Applications)). The DAO is a technology built upon smart contracts and cryptocurrencies. It serves as a self-governing entity that interacts with various other components according to a predefined set of rules. These rules can also be changed by members of the organizations by voting. 

The concept of a DAO is very new and therefore they have an unclear legal status. For example, there are questions surrounding whether investors of a DAO are liable if the DAO makes an illegal decision([Wang et al., 2019b](https://www.researchgate.net/publication/335800811_Decentralized_Autonomous_Organizations_Concept_Model_and_Applications)). Security is also a large concern with DAOs because an exploit in a smart contract in the first world's first DAO (called "The DAO") suffered from [a hack](https://www.forbes.com/sites/cathyhackl/2021/06/01/what-are-daos-and-why-you-should-pay-attention/?sh=4b7402287305) that cost its owners 50$ million worth of Ethereum. Lastly, there may also be issues navigating the "semantic gap" when programmers are translating the high-level (and often non-specific) behavior desired in the DAO into the strict formal syntax required by smart contract languages ([Wang et al., 2019b](https://www.researchgate.net/publication/335800811_Decentralized_Autonomous_Organizations_Concept_Model_and_Applications)). DAOs are an excellent example of a technology empowered by a Blockchain foundation, and practitioners should be made aware of the potential developments surrounding this concept because they may become more common as their common problems start to find working solutions.

### Non-Fungible Tokens (NFTs)

A [Non-Fungible Token(NFT)](https://www.forbes.com/advisor/investing/nft-non-fungible-token/) is an entity stored on the blockchain that represents ownership of a specific digital or real-world asset. Built upon the same technology as cryptocurrencies, NFTs can interact with smart contracts and therefore give developers the ability to create their own dApps that autonomously interact with or transfer NFTs to participants depending on various conditions. For example, an exclusive online club can manage its membership via NFTs. A club can create and distribute an initial number of memberships at a specific price. If club membership has become more exclusive over time and a member is no longer interested, they can sell their membership to another new member. Using smart contracts programmed into the NFT, the club can include specific requirements for the new owner before the sale takes place and can even program in a small fee every time the membership is resold. NFTs are already very popular for the ownership of digital art and are starting to see adoption in the form of [event ticketing](https://www.leewayhertz.com/how-nft-ticketing-works/).

NFTs give more control to individuals over the ownership of their digital content, and they are novel in that they can represent a digital form of scarcity in a world where most digital assets like pictures, videos, and text can be copied repeatedly for little cost. NFTs are already popular in the art world, and practitioners should be aware of the potential for this technology to be integrated into various types of applications such as ticketing, gaming, and other industries yet to find a use case for it.

----

[**Next: Learning Resources**](blockchain_learning.md)

[**Home**](home.md)
