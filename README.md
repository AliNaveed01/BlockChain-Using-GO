This project is a simple implementation of a blockchain in Go. The blockchain consists of blocks containing transactions and is used to demonstrate basic blockchain functionality, including adding blocks, changing transactions, listing blocks, and verifying the integrity of the blockchain.

## Version

Current version: 1.0.0

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)

## Overview

The project defines a basic blockchain structure (`Block`) and provides functions for calculating block hashes, inserting new blocks, changing transactions, listing blocks, and verifying the integrity of the blockchain.

## Project Structure

- **main.go:** The main entry point of the blockchain program.
- **block.go:** Defines the `Block` struct and functions for calculating hashes, inserting blocks, changing transactions, listing blocks, and verifying the blockchain.

## Getting Started

### Prerequisites

1. Go installed on your machine.

### Installation

Clone the repository:

```bash
git clone https://github.com/your-username/simple-blockchain-go.git
cd simple-blockchain-go
```

## Usage

1. Run the blockchain program:

```bash
go run main.go
```

2. View the initial blockchain:

   The program will display the initial blockchain with transactions.

3. Change a transaction:

   Modify the `ChangeBlock` function call in `main.go` to change a transaction in the blockchain.

4. Verify the integrity of the blockchain:

   Run the `VerifyChain` function to check the integrity of the blockchain.

5. Insert a new block:

   Modify the `InsertBlock` function call in `main.go` to insert a new block with transactions.

6. View the updated blockchain:

   The program will display the updated blockchain with the changed transaction or inserted block.

## Contributing

Contributions to this project are welcome. Feel free to open an issue or submit a pull request for improvements or bug fixes.
