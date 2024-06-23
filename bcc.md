# unit-1

1. **Definition of Blockchain**:
   Blockchain is a distributed ledger technology that enables secure, transparent, and immutable record-keeping of transactions across a network of computers. It consists of a chain of blocks, where each block contains a cryptographic hash of the previous block, timestamped transaction data, and a unique identifier. This chain ensures the integrity and chronological order of transactions, making it extremely difficult for any single entity to tamper with the data without detection.

2. **Reasons for the Popularity of Blockchain**:
   - Security: Blockchain uses cryptographic techniques to secure data, making it highly resistant to tampering and fraud.
   - Transparency: The decentralized nature of blockchain allows all participants to view the entire transaction history, promoting transparency and trust.
   - Decentralization: By eliminating the need for intermediaries, blockchain reduces costs and eliminates single points of failure.
   - Efficiency: Blockchain streamlines processes by automating trust and verification, reducing paperwork and delays.
   - Innovation: Blockchain enables new business models and applications, driving innovation across various industries.

3. **Advantages of Blockchain**:
   - Immutability: Once data is recorded on the blockchain, it cannot be altered or deleted, ensuring data integrity.
   - Security: Blockchain uses cryptographic techniques to secure transactions, making it highly resistant to tampering and fraud.
   - Transparency: All participants have access to the same ledger, promoting transparency and trust.
   - Decentralization: Blockchain operates on a distributed network, eliminating the need for intermediaries and reducing the risk of single points of failure.
   - Efficiency: Blockchain automates trust and verification processes, reducing paperwork and delays.
   - Cost Reduction: By eliminating intermediaries and streamlining processes, blockchain reduces transaction costs.
   - Traceability: The transparent nature of blockchain enables easy tracing of transactions, enhancing accountability and auditability.

4. **Limitations of Blockchain**:
   - Scalability: Blockchain networks face challenges in handling a large number of transactions simultaneously, leading to scalability issues.
   - Energy Consumption: Proof-of-Work consensus mechanisms, used in some blockchains, require significant computational power, resulting in high energy consumption.
   - Regulatory Uncertainty: Regulatory frameworks around blockchain and cryptocurrencies are still evolving, leading to uncertainty and compliance challenges.
   - Privacy Concerns: While transactions are pseudonymous, blockchain data is public, raising privacy concerns for some use cases.
   - Adoption Hurdles: Implementing blockchain technology requires significant investment and changes to existing processes, posing adoption challenges for some organizations.

5. **Benefits of Blockchain**:
   - Trust: Blockchain enables trust among participants by providing a transparent and immutable record of transactions.
   - Security: Blockchain uses cryptographic techniques to secure transactions, making it highly resistant to tampering and fraud.
   - Efficiency: Blockchain automates trust and verification processes, reducing paperwork and delays.
   - Cost Reduction: By eliminating intermediaries and streamlining processes, blockchain reduces transaction costs.
   - Innovation: Blockchain enables new business models and applications, driving innovation across various industries.

6. **Genesis Block**:
   The genesis block is the first block in a blockchain. It serves as the foundation of the entire blockchain network and does not reference any previous block. The creation of the genesis block marks the beginning of the blockchain's history. It typically contains special data or a message and is hardcoded into the protocol of the blockchain.

7. **Types of P2P Networks**:
   - Unstructured P2P Networks: In unstructured P2P networks, nodes connect to each other without following any specific organizational pattern. Examples include Gnutella and BitTorrent.
   - Structured P2P Networks: Structured P2P networks organize nodes into a specific topology or structure to facilitate efficient data lookup and retrieval. Examples include Distributed Hash Tables (DHTs) used in systems like Chord and Kademlia.

8. **Features of P2P Networks**:
   - Decentralization: P2P networks operate without central servers, with each node having equal status and capability.
   - Scalability: P2P networks can scale efficiently as new nodes can join or leave the network dynamically without affecting its overall operation.
   - Fault Tolerance: P2P networks are resilient to node failures or attacks as the absence of central servers means that the network can continue to function even if some nodes are compromised.
   - Self-Organization: P2P networks can self-organize and adapt to changes in the network topology without requiring central coordination.
   - Distributed Data Storage: P2P networks distribute data across multiple nodes, ensuring redundancy and improving data availability.

9. **Applications of P2P Networks**:
   - File Sharing: P2P networks are widely used for sharing files and media content, enabling users to distribute and access files without relying on centralized servers.
   - Content Delivery: P2P networks can be used for content delivery, allowing users to access content from nearby peers rather than distant servers, thereby reducing latency and bandwidth costs.
   - Distributed Computing: P2P networks can harness the computational power of multiple nodes to perform complex tasks such as distributed computing or data processing.
   - Messaging and Communication: P2P networks can facilitate peer-to-peer messaging and communication without relying on centralized servers, ensuring privacy and security.
   - Blockchain and Cryptocurrencies: Blockchain networks rely on P2P communication to propagate transactions and maintain the integrity of the ledger.

10. **Advantages of P2P Networks**:
    - Decentralization: P2P networks operate without central servers, providing greater resilience and reducing the risk of single points of failure.
    - Scalability: P2P networks can scale efficiently as new nodes can join or leave the network dynamically without affecting its overall operation.
    - Fault Tolerance: P2P networks are resilient to node failures or attacks as the absence of central servers means that the network can continue to function even if some nodes are compromised.
    - Distributed Data Storage: P2P networks distribute data across multiple nodes, ensuring redundancy and improving data availability.
    - Self-Organization: P2P networks can self-organize and adapt to changes in the network topology without requiring central coordination.

11. **Disadvantages of P2P Networks**:
    - Security Concerns: P2P networks can be vulnerable to security threats such as malware, phishing, and denial-of-service attacks.
    - Quality of Service: P2P networks may suffer from variable performance and reliability as they rely on the resources and connectivity of individual nodes.
    - Legal and Regulatory Challenges: P2P networks may face legal and regulatory challenges, especially in the context of copyright infringement and illegal activities.
    - Privacy Risks: P2P networks may raise privacy concerns as data is shared directly between peers without intermediaries, potentially exposing sensitive information.
    - Network Overhead: P2P networks may incur additional overhead in managing peer connections and maintaining network topology, impacting performance and efficiency.

12. **Distributed Ledger Technology (DLT)**:
    Distributed Ledger Technology (DLT) is a decentralized database that records transactions across multiple locations in a synchronized and secure manner. It enables participants to share and maintain a consensus on the state of a ledger without the need for central authority. Blockchain is a specific type of DLT that uses cryptographic techniques to secure transactions and maintain an immutable record of data. Other forms of DLT include Directed Acyclic Graphs (DAGs), which use a different data structure to achieve similar goals. DLT has applications in finance, supply chain management, healthcare


# unit -2


1. **Steps of Bitcoin Mining**:
   - **Step 1: Node Setup**: Miners set up their computer nodes with Bitcoin software, connecting to the Bitcoin network.
   - **Step 2: Transaction Verification**: Miners collect and verify transactions from the Bitcoin mempool (memory pool), ensuring they are valid according to the network's rules.
   - **Step 3: Block Construction**: Miners group verified transactions into a block and include a special transaction called the "coinbase transaction," which rewards the miner with newly minted bitcoins and transaction fees.
   - **Step 4: Proof of Work**: Miners compete to solve a cryptographic puzzle (Proof of Work) by finding a hash value that meets a certain criteria set by the network difficulty. This process requires significant computational power.
   - **Step 5: Block Propagation**: Once a miner solves the puzzle, they broadcast the new block to the network for validation and inclusion in the blockchain.
   - **Step 6: Consensus**: Other nodes in the network validate the new block, ensuring all transactions within it are legitimate and that the Proof of Work is valid.
   - **Step 7: Block Reward**: If the block is accepted by the network, the miner receives the block reward (currently 6.25 bitcoins) plus any transaction fees associated with the transactions in the block.

2. **Mining Pools**:
   Mining pools are groups of miners who combine their computational resources to increase their chances of successfully mining a block and earning rewards. Pool members contribute their computing power collectively, and when a block is successfully mined, the rewards are distributed among pool participants based on their contribution.

3. **Mining Algorithm**:
   The mining algorithm used in Bitcoin is called SHA-256 (Secure Hash Algorithm 256-bit). Miners use this algorithm to hash the block header and nonce repeatedly until they find a hash value that meets the network's difficulty target. The SHA-256 algorithm ensures that the process is computationally difficult and random, requiring miners to expend significant computational resources to find a valid block hash.

4. **Hardness of Mining**:
   Mining hardness refers to the level of difficulty involved in successfully mining a block on the blockchain. As more miners join the network and computational power increases, the difficulty of the cryptographic puzzle (Proof of Work) also increases. This hardness ensures that blocks are mined at a predictable rate, maintaining the security and integrity of the blockchain.

5. **Types of Bitcoin Wallets**:
   - **Hardware Wallets**: Physical devices that store the user's private keys offline, providing enhanced security.
   - **Software Wallets**: Applications or software programs that store private keys on a computer or mobile device.
   - **Paper Wallets**: Physical documents containing the user's private keys or QR codes for offline storage.
   - **Web Wallets**: Wallets hosted on online platforms or exchanges, accessible through a web browser.
   - **Mobile Wallets**: Wallet applications designed for mobile devices, offering convenience and portability.

6. **Intentional Forks**:
   Intentional forks occur when developers and stakeholders deliberately introduce changes to the blockchain protocol, resulting in a divergence of the blockchain's history. These forks can be planned upgrades or changes to the network's rules, aiming to improve functionality, scalability, or security.

7. **Code-Based Forks**:
   Code-based forks occur when there is a disagreement within the community regarding proposed changes to the blockchain protocol. This results in a split in the network, with one faction following the original protocol and another adopting the new rules. Code-based forks can be contentious and may lead to the creation of new cryptocurrencies.

8. **Reasons for Forks in Blockchain**:
   - Disagreements Over Protocol Changes: Differences in opinion among developers and stakeholders regarding proposed changes to the blockchain protocol.
   - Software Bugs or Vulnerabilities: Discovery of critical bugs or vulnerabilities in the blockchain software that require immediate action to fix.
   - Desire for Innovation or Improvement: Intentional forks initiated by developers to introduce new features, improve scalability, or address security concerns.

9. **Bitcoin Scripts**:
   Bitcoin Scripts are a scripting language used to define the conditions under which bitcoins can be spent. These scripts are embedded in transaction outputs and typically specify cryptographic conditions that must be met for the recipient to spend the bitcoins. Bitcoin Scripts enable various types of transactions, including multi-signature transactions, time-locked transactions, and conditional payments.

10. **Distributed Consensus**:
    Distributed consensus refers to the collective agreement among nodes in a decentralized network regarding the state of the network and the validity of transactions. In blockchain networks like Bitcoin, distributed consensus is achieved through mechanisms such as Proof of Work or Proof of Stake, where nodes compete or cooperate to validate and record transactions in a secure and decentralized manner. Consensus algorithms ensure that all participants in the network reach an agreement on the order and validity of transactions, maintaining the integrity of the blockchain.


# unit- 3

1. **Proof of Work (PoW)**:
   Proof of Work is a consensus mechanism used in blockchain networks to achieve distributed consensus and validate transactions. In PoW, miners compete to solve complex mathematical puzzles, requiring significant computational power. The first miner to find a solution broadcasts it to the network, and other nodes verify the solution before adding the new block to the blockchain. PoW ensures network security by making it computationally expensive to attack the network, as attackers would need to control a majority of the network's computational power.

2. **Attacks on Proof of Work (PoW)**:
   - **51% Attack**: Occurs when an entity gains control of more than 50% of the network's computational power, enabling them to manipulate transactions, double-spend coins, or prevent new transactions from being confirmed.
   - **Selfish Mining**: Involves miners withholding solved blocks from the network, strategically releasing them to gain a competitive advantage and potentially controlling the blockchain's progression.
   - **Sybil Attack**: Involves creating multiple fake identities or nodes to gain control over the network or influence its operations.

3. **Proof of Stake (PoS)**:
   Proof of Stake is an alternative consensus mechanism used in blockchain networks, where validators are chosen to create new blocks based on their ownership or stake of the cryptocurrency. In PoS, validators are selected randomly to propose and validate blocks, and their chances of being chosen depend on the amount of cryptocurrency they hold and are willing to "stake" as collateral. PoS is considered more energy-efficient than PoW as it does not require miners to solve complex mathematical puzzles.

4. **Differences between Permissioned and Permissionless Blockchains**:
   - **Permissioned Blockchain**: In a permissioned blockchain, access to participate in the network and validate transactions is restricted to authorized participants or nodes. These networks are typically used in enterprise settings where privacy, control, and compliance are paramount.
   - **Permissionless Blockchain**: In a permissionless blockchain, anyone can join the network, participate in transaction validation, and create new blocks. Examples include Bitcoin and Ethereum. Permissionless blockchains prioritize decentralization, transparency, and censorship resistance.

5. **Proof of Authority (PoA)**:
   Proof of Authority is a consensus mechanism where validators are chosen based on their reputation or authority within the network. Validators are typically known entities or organizations approved by the network participants. In PoA, validators are responsible for creating new blocks and validating transactions. PoA is often used in private or consortium blockchains where trust among participants is established, and strict governance is maintained. It is more efficient than PoW and PoS in terms of energy consumption and scalability.


# unit 3 part B

## what is Ethereum

Ethereum is a Blockchain network that introduced a built-in Turing-complete programming language that can be used for creating various decentralized applications(also called Dapps). The Ethereum network is fueled by its own cryptocurrency called ‘ether’. 

•	The Ethereum network is currently famous for allowing the implementation of smart contracts. Smart contracts can be thought of as ‘cryptographic bank lockers’ which contain certain values. 

•	These cryptographic lockers can only be unlocked when certain conditions are met. 

•	Unlike bitcoin, Ethereum is a network that can be applied to various other sectors. 

•	Ethereum is often called Blockchain 2.0 since it proved the potential of blockchain technology beyond the financial sector. 

•	The consensus mechanism used in Ethereum is Proof of Stakes(PoS), which is more energy efficient when compared to that used in the Bitcoin network, that is, Proof of Work(PoW). PoS depends on the amount of stake a node holds. 

### Drawbacks of Ethereum

•	**Complicated programming language**: Learning solidity from programming smart contracts on Ethereum can be challenging and one of the main concerns is the scarcity of beginner-friendly classes.

•	**Volatile cryptocurrency**: Ethereum investing can be risky as the price of Ether is very volatile, resulting in significant gains as well as a significant loss.

•	**Low transaction rate**: Bitcoin has an average transaction rate of 7TPS and Ethereum has an average speed of 15 TPS which is almost double that of bitcoin but it is still not enough.

### Benefits of Ethereum

•	Availability
•	Privacy
•  Security 
•	Less ambiguity
•	Rapid deployment
•	Network size 
•	Data coordination


### How Does Ethereum Work?
Ethereum implements an execution environment called Ethereum Virtual Machine (EVM).

•	When a transaction triggers a smart contract all the nodes of the network will execute every instruction.

•	All the nodes will run The EVM as part of the block verification, where the nodes will go through the transactions listed in the block and runs the code as triggered by the transaction in the EVM.

•	All the nodes on the network must perform the same calculations for keeping their ledgers in sync.

•	Every transaction must include:
o	Gas limit.
o	Transaction Fee that the sender is willing to pay for the transaction.

•	If the total amount of gas needed to process the transaction is less than or equal to the gas limit then the transaction will be processed and if the total amount of the gas needed is more than the gas limit then the transaction will not be processed the fees are still lost.

•	Thus it is safe to send transactions with the gas limit above the estimate to increase the chances of getting it processed.

### Characteristics of Ethereum Blockchain

1.	Smart contracts: Ethereum allows the creation and deployment of smart contracts. Smart contracts are created mainly using a programming language called solidity. Solidity is an Object Oriented Programming language that is comparatively easy to learn. 
2.	Ethereum Virtual Machine (EVM): It is designed to operate as a runtime environment for compiling and deploying Ethereum-based smart contracts.
3.	Ether: Ether is the cryptocurrency of the Ethereum network. It is the only acceptable form of payment for transaction fees on the Ethereum network. 
4.	Decentralized applications (Daaps): Dapp has its backend code running on a decentralized peer-to-peer network. It can have a frontend and user interface written in any language to make calls and query data from its backend. They operate on Ethereum and perform the same function irrespective of the environment in which they get executed.
5.	Decentralized autonomous organizations (DAOs): It is a decentralized organization that works in a democratic and decentralized fashion. DAO relies on smart contracts for decision-making or decentralized voting systems within the organization.


### Type of Ethereum Accounts

•	**Externally owned account (EOA):** Externally owned accounts are controlled by private keys. Each EOA has a public-private key pair. The users can send messages by creating and signing transactions.

•	**Contract Account:** Contract accounts are controlled by contract codes. These codes are stored with the account. Each contract account has an ether balance associated with it. The contract code of these accounts gets activated every time a transaction from an EOA or a message from another contract is received by it. When the contract code activates, it allows to read/write the message to the local storage, send messages and create contracts.


### Real-World Applications of Ethereum
1. Voting
2. Agreement
3. Banking system
4. Shipping
5. Crowdfunding
6. Domain names

### Discuss any three (Metamask, Myether, Coinbase) EVM Wallets

#### 1. MetaMask


MetaMask is a widely-used Ethereum wallet available as a browser extension and mobile app. It allows users to manage private keys and interact with decentralized applications (dApps).

**Key Features:**
- **Browser Integration:** Works with Chrome, Firefox, Brave, and Edge.
- **User-Friendly Interface:** Simple for both beginners and advanced users.
- **Security:** Private keys are encrypted and stored locally; supports hardware wallets.
- **dApp Access:** Seamless interaction with DeFi platforms and NFT marketplaces.

**Drawbacks:**
- **Phishing Risks:** Susceptible to phishing attacks due to its nature as a browser extension.
- **Privacy Concerns:** Being a hot wallet, it's less secure compared to cold storage.

#### 2. MyEtherWallet (MEW)


MyEtherWallet is an open-source, web-based interface for interacting with the Ethereum blockchain. It provides a platform for managing funds, smart contracts, and dApps.

**Key Features:**
- **Web Interface:** Allows creation and management of Ethereum wallets.
- **Hardware Wallet Support:** Compatible with Ledger, Trezor, and others for enhanced security.
- **Customization:** Users can set custom gas fees for transactions.
- **MEWconnect:** Companion mobile app for secure wallet access.

**Drawbacks:**
- **Security:** Requires vigilance against phishing sites.
- **Complexity:** Interface may be overwhelming for new users.

#### 3. Coinbase Wallet


Coinbase Wallet is a mobile app and browser extension developed by Coinbase. It allows users to manage their crypto assets and interact with Ethereum dApps.

**Key Features:**
- **Mobile and Browser Extension:** Available for iOS, Android, and as a browser extension.
- **Security:** Private keys are stored locally with cloud backup options.
- **Integration with Coinbase:** Easy transfer of funds between Coinbase Wallet and Coinbase exchange accounts.
- **dApp Access:** Direct access to DeFi applications and NFT marketplaces.

**Drawbacks:**
- **Privacy:** Cloud backups introduce potential security risks.
- **Ecosystem Dependence:** Heavily integrated with Coinbase services.



## Smart Contracts in Blockchain

  A Smart Contract (or cryptocontract) is a computer program that directly and automatically controls the transfer of digital assets between the parties under certain conditions. A smart contract works in the same way as a traditional contract while also automatically enforcing the contract. Smart contracts are programs that execute exactly as they are set up(coded, programmed) by their creators. Just like a traditional contract is enforceable by law, smart contracts are enforceable by code.   

• The bitcoin network was the first to use some sort of smart contract by using them to transfer value from one person to another. 

•	The smart contract involved employs basic conditions like checking if the amount of value to transfer is actually available in the sender account. 

•	Later, the Ethereum platform emerged which was considered more powerful, precisely because the developers/programmers could make custom contracts in a Turing-complete language.

•	It is to be noted that the contracts written in the case of the bitcoin network were written in a Turing-incomplete language, restricting the potential of smart contracts implementation in the bitcoin network. 

•	There are some common smart contract platforms like Ethereum, Solana, Polkadot, Hyperledger fabric, etc.

### Features of Smart Contracts

1. Distributed
2. Deterministic
3. Immutable
4. Autonomy
5. Customizable
6. Transparent
7. Trustless
8. Self-verifying
9. Self-enforcing

### Capabilities of Smart Contracts

1.  Accuracy
2.  Automation
3.  Speed
4.  Backup
5.  Security
6.  Saving
7.  Manges information
8.  Multi-signature accounts




### Smart Contract Working

• Identify Agreement: Multiple parties identify the cooperative opportunity and desired outcomes and agreements could include business processes, asset swaps, etc.

•	Set conditions: Smart contracts could be initiated by parties themselves or when certain conditions are met like financial market indices, events like GPS locations, etc.

•	Code business logic: A computer program is written that will be executed automatically when the conditional parameters are met.

•	Encryption and blockchain technology: Encryption provides secure authentication and transfer of messages between parties relating to smart contracts.

•	Execution and processing: In blockchain iteration, whenever consensus is reached between the parties regarding authentication and verification then the code is executed and the outcomes are memorialized for compliance and verification.

•	Network updates: After smart contracts are executed, all the nodes on the network update their ledger to reflect the new state. Once the record is posted and verified on the blockchain network, it cannot be modified, it is in append mode only.


### Applications of Smart Contracts

1.	Real Estate: Reduce money paid to the middleman and distribute between the parties actually involved. For example, a smart contract to transfer ownership of an apartment once a certain amount of resources have been transferred to the seller’s account(or wallet).
2.	Vehicle ownership: A smart contract can be deployed in a blockchain that keeps track of vehicle maintenance and ownership. The smart contract can, for example, enforce vehicle maintenance service every six months; failure of which will lead to suspension of driving license.
4.	Music Industry: The music industry could record the ownership of music in a blockchain. A smart contract can be embedded in the blockchain and royalties can be credited to the owner’s account when the song is used for commercial purposes. It can also work in resolving ownership disputes.
5.	Government elections: Once the votes are logged in the blockchain, it would be very hard to decrypt the voter address and modify the vote leading to more confidence against the ill practices.
6.	Management: The blockchain application in management can streamline and automate many decisions that are taken late or deferred. Every decision is transparent and available to any party who has the authority(an application on the private blockchain). For example, a smart contract can be deployed to trigger the supply of raw materials when 10 tonnes of plastic bags are produced.
7.	Healthcare: Automating healthcare payment processes using smart contracts can prevent fraud. Every treatment is registered on the ledger and in the end, the smart contract can calculate the sum of all the transactions. The patient can’t be discharged from the hospital until the bill has been paid and can be coded in the smart contract

### VALUE TYPES
•	Value types are data types that hold a value directly and are not pointers to memory locations.
•	Value types in Solidity are passed by value.
•	Value type data types in solidity are listed below:
    1. Boolean : True or False
    2. Integer : int & uint
    3. Address : Size of Ethereum address(20 bytes)
    4. Bytes : Character set(1-32 length)
    5. Enums : User defined data types

    
#### ARRAYS

•	Arrays are data structures that store the fixed collection of elements of the same data types in which each and every element has a specific location called index.

•	Arrays can be used in a wide range of Solidity applications, from storing lists of user addresses or transaction data to implementing more complex data structures like maps and graphs. 

•	However, care must be taken to ensure that array operations are gas-efficient and do not exceed the gas limit for a particular transaction.

•	Syntax : <data type> <array name> [size] = <initialization>

**TYPES OF ARRAYS**

**1. Fixed size arrays**
•	The size of the array should be predefined. The total number of elements should not exceed the size of the array. 
•	Ex : - uint[6] data1;

**2. Dynamic arrays**
   
•	The size of the array is not predefined when it is declared. As the elements are added the size of array changes and at the runtime, the size of the array will be determined.

•	Ex : -  int[ ] data1;

#### FUNCTIONS

•	Functions are blocks of code that perform a specific task, such as updating data on the blockchain or returning a value to the user.

•	They can be declared as public, private, and internal, which determine whether they can be called by other contracts or only by the contract itself.

•	They have different types of return values, including void, integers, Booleans, or custom data structures.

•	They can also include parameters, which are inputs that are passed to the function.

•	Synatx :    function function_name(parameter_list) scope
   	       returns(return_type){
                               //block of code
}

•	Functions can be used for a wide range of purposes, from simple data manipulation to complex business logic and smart contract interactions, and they are a key component of writing efficient and secure smart contracts on the Ethereum blockchain.

•	Ex :-  function add() public pure returns(uint) {
           		unit num1 = 10;
		uint num2  = 16;
		uint sum = num1 + num2;
		return sum;
	 }
  
#### STRUCTS

•	Structs are user-defined data structures that can contain multiple variables of different data types.

•	They can be defined within a contract and can be used to represent complex data types, such as a user profile or a transaction record.

•	Structs can be passed as parameters to functions and returned as values, allowing for the creation of more flexible and modular code structures in Solidity smart contracts.

•	Syntax :- struct <structure_name>{
		<data type> variable_1;
		<data type> variable_2;
	      }
       
•	Structs in Solidity can also include functions, allowing for the definition of complex behaviors and interactions between different data structures.

•	Ex : - struct student{
		string name;
		string subject;
		uint8 marks;
	}
#### MAPPING
•	Mapping is a key-value data structure that allows for efficient storage and retrieval of data on the Ethereum blockchain.

•	It can be defined within a contract and can be used to associate a key of one data type with a value of another data type.

•	They are similar to dictionaries or hash tables in other programming languages, and they can be used to store a wide range of data, including user balances, transaction records, and smart contract states.

•	Syntax : mapping(key => value) <access specifier>  <name>;

•	They are used in combination with other data structures like arrays and structs, allowing for the creation of more complex data structures like maps and graphs.

•	Mappings in Solidity are gas-efficient and offer a fast and reliable way to store and retrieve data on the Ethereum blockchain, making them a popular choice for smart contract developers.

•	Ex :- mapping(
	    address => student) result;
	    address[] public student_result;

