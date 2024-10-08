## 🚀 Project Overview

**Tagline:**  
File Storage in IPFS and CID stored in blockchain which reduces the gas cost and the file is encrypted using ECC. Verification of the original file is done using the PaddleOCR model.

### 📝 The Problem it Solves

The project aims to create a **Comprehensive Automated Document Verification System** using **Blockchain**, **Interplanetary File System (IPFS)**, and **Artificial Intelligence (AI)**. This system securely stores and verifies official documents, leveraging blockchain technology for decentralized storage and data protection.

- **Document Storage**: Uses MetaMask wallet addresses to ensure only authorized users can access the documents.
- **Encryption**: Documents are encrypted using **Elliptic Curve Cryptography (ECC)** for secure transmission.
- **Verification**: A unique hash is generated from document metadata, extracted by an AI-powered OCR system (**PaddleOCR**), enabling fast, accurate verification in under a minute.

This solution allows organizations and individuals to grant access to documents by setting permissions, giving certificate holders full control over who can view the documents.

### 💡 Challenges We Ran Into

**Technical Challenges**:  
Verifying low-quality images proved difficult, as poor image quality can prevent accurate metadata extraction and verification. Integrating technologies like IPFS, Polygon, and ECC also required overcoming complexities in decentralized data storage and transmission.

**Financial Challenges**:  
The cost of gas fees was a concern for users. By implementing **Polygon's zkEVM**, we significantly reduced transaction costs, easing the burden for users.

**Market Challenges**:  
Convincing organizations to shift from centralized to decentralized systems was challenging. Familiarity with traditional methods slowed adoption of blockchain technology.

**Operational Challenges**:  
User access management was crucial, as losing wallet addresses or passwords would prevent access to documents. A recovery mechanism involving credential verification by authorized officials was proposed.

### 🛠️ Technologies We Used

- ⚛️ React.js
- ⚡ ethers.js
- 🛠️ Hardhat
- 🔐 Solidity
- 🛡️ Polygon
- 📁 IPFS
- 🔑 ECDSA
- 🌐 Flask
- 🔍 OCR
- ⛓️ Ethereum

### 🛠️ Steps to Set Up the Project

Follow these steps to get the project up and running on your local machine:

## 1. Clone the Repository

git clone https://github.com/your-repo/project-name.git
cd project-name

## 2. Install Dependencies

Navigate to the project directory and install the required dependencies:

npm install

## 3. Set Up Necessary Variables

INFURA_API_KEY=your-infura-api-key
PRIVATE_KEY=your-wallet-private-key
IPFS_GATEWAY=your-ipfs-gateway

Replace the placeholders with your actual keys and values.
## 4. Compile the Smart Contracts

Compile the smart contracts using Hardhat:

npx hardhat compile

## 5. Deploy the Smart Contracts

Deploy the contracts to the desired network (e.g., Polygon zkEVM):

npx hardhat ignition deploy ignition/modules/Lock.js --network zkEVM  --deployment-id <DeploymentId>    

## 6. Run the Frontend

Start the frontend application:

npm run dev

On both the react apps

## 7. Interact with the Application

    Open your browser and navigate to http://localhost:5173 & 5154.
    Connect your MetaMask wallet to interact with the smart contracts.
    Start uploading and verifying documents through the decentralized platform!

## 🔄 Workflow
![WhatsApp Image 2024-09-11 at 18 32 40_1299ebd8](https://github.com/user-attachments/assets/b821960b-9708-4e03-9208-3448e01f738e)
![WhatsApp Image 2024-10-08 at 10 08 08_811cf635](https://github.com/user-attachments/assets/67d086be-0ad0-47e6-9fe7-ff8f11006d80)
![WhatsApp Image 2024-10-08 at 10 08 08_879b3a30](https://github.com/user-attachments/assets/2074c084-b73a-41fb-b323-a215114eab05)

