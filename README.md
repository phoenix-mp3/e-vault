# Blockchain-based eVault for Legal Records

The **eVault** system is designed for secure and efficient legal records management using blockchain technology. It leverages MetaMask for cryptocurrency transactions, ensuring robust user authentication and document handling. This platform provides a user-friendly React-based dashboard for accessing, searching, and managing legal documents with enhanced security features.

## 🚀 Project Overview

The eVault system addresses the limitations of traditional centralized systems by integrating blockchain for decentralized identity management and document verification. It includes:

- **MetaMask Integration:** Facilitates Ethereum-based transactions and interactions with decentralized applications (DApps).
- **User Dashboard:** A React-developed interface providing an overview and management of legal records.
- **Access Control & Encryption:** Implements role-based access control (RBAC) and end-to-end encryption to safeguard data.
- **Document Verification:** Allows viewing of verified documents with detailed verification steps and version history.

## 🔧 Technology Stack

- **Blockchain:** Ethereum, Web3, Solidity, IPFS, Truffle.
- **Front End:** React JS, Bootstrap.
- **Back End:** NodeJS.
- **Database:** MongoDB.
- **Hosting Services:** Heroku (React DApp), MLAB (MongoDB), Infura (Blockchain), MetaMask.

## 📦 Installation & Setup

### Prerequisites

1. **Node.js:** Ensure Node.js is installed for backend and frontend development.
2. **MetaMask:** Install MetaMask for Ethereum wallet integration.

### Clone the Repository

```bash
git clone https://github.com/yourusername/blockchain-based-evault.git
cd blockchain-based-evault
```

### Install Dependencies

```bash
npm install
```

### Running the Application

- **Frontend:** 

  Navigate to the frontend directory and start the React application.

  ```bash
  cd client
  npm start
  ```

- **Backend:**

  Start the NodeJS server.

  ```bash
  cd server
  npm start
  ```

## 📖 Features

### MetaMask Integration

- Enables cryptocurrency transactions within the eVault system.
- Users can pay for legal services using Ether tokens through MetaMask.

### User Dashboard

- Provides a comprehensive overview of legal records.
- Includes features for searching, filtering, and managing documents.

### Access Control & Encryption

- **User Roles:** Admins, lawyers, judges, and clients with specific privileges.
- **Role-Based Access Control (RBAC):** Assigns access levels to different user roles.
- **End-to-End Encryption:** Protects data in transit and ensures document confidentiality.
- **Document-Level Encryption:** Secures individual documents with strong cryptographic algorithms.

### Document Verification

- Visual indicators of document authenticity and integrity.
- Detailed verification steps and timestamps.
- Version history tracking for changes and updates.
