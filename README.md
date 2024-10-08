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

## 🔄 Workflow
