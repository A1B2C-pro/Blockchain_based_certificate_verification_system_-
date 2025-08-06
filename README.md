# Blockchain_based_certificate_verification_system_-
Certifier DApp is a decentralized web application built on the Ethereum blockchain. It allows authorized users to issue, update, verify, and track the change history of digital certificates securely and transparently. This project showcases how blockchain can be applied to create a secure, tamper-proof, and transparent certification system.

## Features
- Signin with Ethereum Wallet (MetaMask)
- Issue New Certificate
- Update Issued Certificates
- Verify Issued Certificates
- Track Change history of Issued Certificates

- ## Authors
- [A1B2C-pro](https://www.github.com/A1B2C-pro)

- ## Tech Stack
- 
- #### Web3
- [Ethers.js](https://docs.ethers.io)
- [Truffle](https://trufflesuite.com/docs/)
- [Solidity](https://soliditylang.org/)

#### Frontend
- [React.js](https://reactjs.org)
- [React Router](https://reactrouter.com/)
- [React Toastify](https://fkhadra.github.io/react-toastify/)

- ## Environment Setup

- Download and install the latest node and npm from https://nodejs.org/en/download/
- Download and install Visual Studio Code from https://code.visualstudio.com/
- Download and install Ganache from https://trufflesuite.com/ganache/
    - Create new Workspace
    - Link this project to workspace
    - Update port number to 8545
    - ![Ganache Setup](https://user-images.githubusercontent.com/95211796/201491935-87f8d7cb-254e-40ff-aaae-290d25134be8.png)

- Install Truffle `npm install truffle -g`
- Link Metamask to Local Blockchain network created by Ganache

- Clone the project

```bash
  git clone https://github.com/aachal01/certifier-dapp.git
```

Go to the project directory

```bash
  cd certifier-dapp
```

Install dependencies

```bash
  npm install
```

Deploy Smart Contract locally

```bash
  npm run contract:deploy
```

Start the server

```bash
  npm run start


