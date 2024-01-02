## Academic Record Storage Using Blockchain
### Introduction:
This project tackles the critical issue of securely storing and sharing educational records in the digital era. While educational documents have increasingly moved online, the challenges of ensuring secure and privacy-conscious storage and sharing remain. Our solution employs a blockchain-based approach, integrating blockchain, a storage database, and cryptography to establish a secure and reliable environment for handling educational records. The system uses blockchain to guarantee data security and reliability, and leverages smart contracts to efficiently manage storage and sharing processes. Educational records are securely stored off-chain in an encrypted format, while their hash information is maintained on the blockchain. This approach ensures continuous synchronization and security of the stored data. Cryptographic techniques are applied for encrypting documents and digitally signing messages, further enhancing data protection. The system features a WebApp interface, facilitating efficient transactions and supporting a decentralized approach for all parties involved.
### Technology Stack:
* Blockchain
    * Ethereum, 
    * Web3, 
    * Solidity,
    * Truffle.
* Front End (Web DApp)
    * React JS, 
    * Bootstrap.
* Back End
    * NodeJS.
* Database
    * OrbitDB.
* Hosting Services
    * Heroku (React DApp),
    * Infura (Blockchain),
    * Metamask.
### SYSTEM DESIGN & ARCHITECTURE:

Visual representations of various interfaces and dashboards are provided to showcase the system's functionality.

![Working](/images/1.png)

#### The login-in interface for student and institute:

Showcasing the entry point for users to access their respective dashboards.

![The login-in interface for student and institute](/images/5.png)

#### The student dashboard to apply for records:

Illustrating the interface where students can apply for and manage their records.

![The student dashboard to apply for records](/images/2.png)

####  Spending ether on transaction using Metamask:

Depicting the process of using Ether for transactions within the system.

![ Spending ether on transaction using Metamask](/images/3.png)

#### Institute dashboard of requested documents:

Displaying the institute's view for managing and responding to document requests.

![Institute dashboard of requested documents](/images/12.png)

#### Representative view of the verified document:

Presenting how verified documents are represented in the system.

![Representative view of the verified document](/images/10.png)



### Instructions to run


1) Install necessary dependencies using "npm install".

 2) Start the application with "npm start".

 3) Set up Metamask and Ganache, and create an account.

 4) Import Ganache details into Metamask.

 5) Access the application locally at "localhost:3000"
