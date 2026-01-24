# Simple Storage Smart Contract 

This repository contains a **beginner-level Solidity smart contract** created using **Remix IDE**. The goal of this project is to understand the **basics of smart contracts**, how to **store and retrieve data on the blockchain**, and how Solidity works.

---

##  About the Project

**Simple Storage** is a basic smart contract that allows users to:

* Store a number on the blockchain
* Retrieve the stored number

This project is ideal for beginners who are just starting their journey in **Blockchain** and **Solidity development**.

---

##  Tech Stack

* **Solidity** (Beginner level)
* **Remix IDE** (Online Ethereum IDE)
* **Ethereum Blockchain (Local / Test Environment)**

---

## Smart Contract Overview

The contract includes:

* A state variable to store data
* A function to update the stored value
* A function to read the stored value

### Example Contract Logic

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract SimpleStorage {
    uint256 private storedNumber;

    function set(uint256 _num) public {
        storedNumber = _num;
    }

    function get() public view returns (uint256) {
        return storedNumber;
    }
}
```

---

## How to Run the Contract (Using Remix IDE)

1. Open **Remix IDE**: [https://remix.ethereum.org/](https://remix.ethereum.org/)
2. Create a new file: `SimpleStorage.sol`
3. Paste the smart contract code
4. Compile the contract using **Solidity Compiler**
5. Deploy the contract using **Deploy & Run Transactions**
6. Use the `set()` function to store a value
7. Use the `get()` function to retrieve the stored value

---

## Learning Outcomes

* Understanding basic Solidity syntax
* Learning how state variables work
* Writing and calling functions in a smart contract
* Deploying a contract using Remix IDE

---

## Future Improvements

* Store multiple values
* Add events
* Restrict access using modifiers
* Connect with a frontend (React + Web3)

---

##  Author

**Tejus  Jaiswal**


---

## ⭐ Support

If you found this project helpful, feel free to **star ⭐ the repository** and share feedback.

Happy Learning! ⛓️🚀
