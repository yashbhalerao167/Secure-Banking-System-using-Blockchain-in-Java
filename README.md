# Secure-Banking-System-using-Blockchain-in-Java
A Spring Boot–based banking backend that manages accounts and fund transfers while recording every transaction on a Hyperledger Fabric blockchain to ensure immutability, auditability, and tamper-proof financial records using a hybrid database + blockchain architecture.


# Secure Banking System with Blockchain-backed Transaction Ledger

A secure, enterprise-style banking backend built using **Java Spring Boot** and **Hyperledger Fabric**, designed to ensure **tamper-proof transaction records** while maintaining high-performance account management using a traditional database.

This project demonstrates how blockchain can be selectively integrated into a banking system to provide **immutability and auditability** without compromising performance.

---

## 🚀 Key Features

- User and bank account management
- Secure fund transfer workflows
- Immutable transaction recording using blockchain
- Hybrid architecture (Database + Blockchain)
- Permissioned blockchain network using Hyperledger Fabric
- Smart contracts (chaincode) for transaction persistence

---

## 🏗️ System Architecture

The system follows a **hybrid enterprise architecture**:

- **Spring Boot Backend**
  - Handles user requests, validations, and business logic
  - Manages account balances and user data
- **Relational Database**
  - Stores users, accounts, and current balances for fast access
- **Hyperledger Fabric Blockchain**
  - Records every financial transaction immutably
  - Acts as a tamper-proof audit ledger

> Account balances are maintained in the database for performance,  
> while transaction integrity is guaranteed via blockchain.

---

## 🔁 Transaction Flow

1. User initiates a fund transfer request
2. Spring Boot backend validates sender, receiver, and balance
3. Account balances are updated in the database
4. Transaction metadata is sent to Hyperledger Fabric
5. Chaincode (smart contract) records the transaction on the blockchain
6. Blockchain commits the transaction immutably
7. API returns success or failure

---

## 🔐 Why Hyperledger Fabric?

- Permissioned blockchain (no anonymous participants)
- Suitable for regulated environments like banking
- Supports enterprise-grade access control
- Faster and more scalable than public blockchains
- Ideal for audit trails and compliance

---

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot
- Spring Data JPA
- REST APIs

### Blockchain
- Hyperledger Fabric
- Chaincode (Smart Contracts)

### Database
- Relational Database (MySQL / PostgreSQL)

### Tools
- Maven
- Git & GitHub
- Docker (for Hyperledger network)

---

