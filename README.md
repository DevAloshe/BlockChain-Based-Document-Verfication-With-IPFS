# BlockChain-Based Document Verification with IPFS

This project aims to create a secure and decentralized system for document verification using Blockchain and InterPlanetary File System (IPFS) technologies. The system stores the hash of the documents in the Blockchain network and the documents themselves in the IPFS network. This ensures that the documents cannot be tampered with or altered, and they can be easily retrieved and verified by authorized parties.

## Features

- Secure document verification using Blockchain and IPFS technologies
- Decentralized system, with no central authority or single point of failure
- Fast and easy verification process, with no need for intermediaries or third-party services
- User-friendly interface for document upload and verification
- Support for multiple document types and formats

## Requirements

- Node.js and npm installed on your system
- MetaMask Wallet
- IPFS API (key and secret) you can get it from infura.io

## Installation

1. Clone this repository: 
``https://github.com/DevAloshe/BlockChain-Based-Document-Verfication-With-IPFS.git``


2. Install the required packages:

``cd BlockChain-Based-Document-Verfication-With-IPFS
npm install``


3. Open the application in your browser using Live Server Extension .


## Usage

1. The owner of the system must first add an exporter to the list of authorized parties. This is done by clicking on the "Add Exporter" button and entering the exporter's Ethereum address.
2. Upload a document to the system by clicking on the "Upload Document" button and selecting a file from your computer. The document will be encrypted and stored in the IPFS network, and its hash will be recorded in the Blockchain.

3. Verify a document by clicking on the "Verify Document" button and entering its unique identifier (hash) in the input field. The system will retrieve the document from the IPFS network, decrypt it, and compare its hash with the one recorded in the Blockchain.

4. The system will display a message indicating whether the document is authentic or not.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
- Metamask documentation
- Solidity and Web3.js documentation
- IPFS documentation
- Truffle documentation



