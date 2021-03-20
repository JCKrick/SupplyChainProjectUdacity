# Supply chain & data auditing

This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

# Contract address and deployment on rinkeby

Supply Chain:  

 Deploying 'SupplyChain'
   -----------------------
   > transaction hash:    0x764e6a3dcd68a91c77c38df997093514d407f0ac192f61378391629f5b09f355
   > Blocks: 0            Seconds: 8
   > contract address:    0xB876F6caAe31558f14bAA75da7116DB95D0428ae
   > block number:        8267979
   > block timestamp:     1616252945
   > account:             0x613b07297B830C8AAad28D67d95EdbD52a039732
   > balance:             1.38872639
   > gas used:            2343684 (0x23c304)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.02343684 ETH


   Deploying 'ConsumerRole'
   ------------------------
   > transaction hash:    0x52e1a82cfc968874392f26910de44b6287d3206d18dd3cbc5c830d7da2a5c701
   > Blocks: 0            Seconds: 8
   > contract address:    0x6A4B55DCf51e8B69F7e9cFb2f6C904307c0Ff43a
   > block number:        8267978
   > block timestamp:     1616252930
   > account:             0x613b07297B830C8AAad28D67d95EdbD52a039732
   > balance:             1.41216323
   > gas used:            313821 (0x4c9dd)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00313821 ETH

    Deploying 'RetailerRole'
   ------------------------
   > transaction hash:    0x1ce83ffe82a8648b18c967d03cdc47cb134d491d750ed636881de21b6f36aca3
   > Blocks: 1            Seconds: 12
   > contract address:    0xb321c5101064af9391D3Aa76f9501e3465F08200
   > block number:        8267977
   > block timestamp:     1616252915
   > account:             0x613b07297B830C8AAad28D67d95EdbD52a039732
   > balance:             1.41530144
   > gas used:            313797 (0x4c9c5)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00313797 ETH

     Deploying 'DistributorRole'
   ---------------------------
   > transaction hash:    0x28fb2ed2e5a7ab0e88bf18eaf040c3e3377fe88713cb97dd7d8a89df5b6a3fbd
   > Blocks: 0            Seconds: 8
   > contract address:    0xc3632316FA161Fc2A9Bbdf19c14ad8A4436Cbf7f
   > block number:        8267976
   > block timestamp:     1616252900
   > account:             0x613b07297B830C8AAad28D67d95EdbD52a039732
   > balance:             1.41843941
   > gas used:            313809 (0x4c9d1)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00313809 ETH

      Deploying 'FarmerRole'
   ----------------------
   > transaction hash:    0x2564301a985a62dccce13f1519eb9591ec1f68f4571c65fbd80c9f3d1fdb276a
   > Blocks: 0            Seconds: 8
   > contract address:    0x017f8b24D93ef598D8Fc1eA1F89Ec82a460931ca
   > block number:        8267975
   > block timestamp:     1616252885
   > account:             0x613b07297B830C8AAad28D67d95EdbD52a039732
   > balance:             1.4215775
   > gas used:            313821 (0x4c9dd)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00313821 ETH



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
