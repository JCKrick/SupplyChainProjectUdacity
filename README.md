# Supply chain & data auditing

This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

# Contract address and deployment on rinkeby

Supply Chain:  

  Deploying 'SupplyChain'
   -----------------------
   > transaction hash:    0x0f74d5463654997d4d5920e19bd05843e8c0a4d58c4167e6e93c5f342a60f00f
   > Blocks: 0            Seconds: 0
   > contract address:    0x5779eB95337AF6c1793fD521De8c897B237c9d79
   > block number:        360
   > block timestamp:     1615288573
   > account:             0x27D8D15CbC94527cAdf5eC14B69519aE23288B95
   > balance:             97.80102098
   > gas used:            2343684 (0x23c304)

Consumer Role:

 > transaction hash:    0xd9adf33e968b3bc48c1406040b961389895b6a8025b820e9ec97c4907a671bf9
   > Blocks: 0            Seconds: 0
   > contract address:    0x94692D7630cD19741223eFE7C05C6c265ceA7496
   > block number:        359
   > block timestamp:     1615288572
   > account:             0x27D8D15CbC94527cAdf5eC14B69519aE23288B95
   > balance:             97.84789466
   > gas used:            313821 (0x4c9dd)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00627642 ETH

   Deploying 'RetailerRole'
   ------------------------
   > transaction hash:    0x3c9bf16edce4327dfdfb90df9fca05867b1d2b5e6eed45dee8a44a55c4e4bb33
   > Blocks: 0            Seconds: 0
   > contract address:    0x580C230558b5E7c3E51c357AA939C98C1AEA8C21
   > block number:        358
   > block timestamp:     1615288572
   > account:             0x27D8D15CbC94527cAdf5eC14B69519aE23288B95
   > balance:             97.85417108
   > gas used:            313797 (0x4c9c5)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00627594 ETH


   Deploying 'DistributorRole'
   ---------------------------
   > transaction hash:    0xbb070cf8b1e151ea4eee6d9379f20c6c288658693d0101136abe0013d833a9be
   > Blocks: 0            Seconds: 0
   > contract address:    0xD3f53Eb6Afa3f3c68107adEb4732Dd7aC918D987
   > block number:        357
   > block timestamp:     1615288571
   > account:             0x27D8D15CbC94527cAdf5eC14B69519aE23288B95
   > balance:             97.86044702
   > gas used:            313785 (0x4c9b9)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.0062757 ETH

   Deploying 'FarmerRole'
   ----------------------
   > transaction hash:    0xa71143f139c276ba40999dfd23cf205715880a2dfa5eb021c542d078205efb4d
   > Blocks: 0            Seconds: 0
   > contract address:    0xA8D2eC9fBb7CED41ccb8Ef335204f375bC20acCc
   > block number:        356
   > block timestamp:     1615288571
   > account:             0x27D8D15CbC94527cAdf5eC14B69519aE23288B95
   > balance:             97.86672272
   > gas used:            313797 (0x4c9c5)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00627594 ETH

   > transaction hash:    0x12699ef38fc7c13a0fb22990ab83af011b2537ace4c907b7f8e397a9d00ea27a
   > Blocks: 0            Seconds: 0
   > contract address:    0x024b04e797b1De7a28d4329e8aB0433338D4f609
   > block number:        354
   > block timestamp:     1615288570
   > account:             0x27D8D15CbC94527cAdf5eC14B69519aE23288B95
   > balance:             97.87384562
   > gas used:            238594 (0x3a402)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00477188 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.00477188 ETH


## Diagrams

* Action Diagram
(/images/Action.pdf)

* Class Diagram
(/images/ClassDiagramm.png)

* Sequence Diagram
(/images/SequenceDiagram.pdf)

* State Diagram
(/images/State.pdf)


## Built With

* [Ethereum](https://www.ethereum.org/) - Ethereum is a decentralized platform that runs smart contracts
* [IPFS](https://ipfs.io/) - IPFS is the Distributed Web | A peer-to-peer hypermedia protocol
to make the web faster, safer, and more open.
* [Truffle Framework](http://truffleframework.com/) - Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.


## Authors

See also the list of [contributors](https://github.com/your/project/contributors.md) who participated in this project.

## Acknowledgments

* Solidity
* Ganache-cli
* Truffle
* IPFS
