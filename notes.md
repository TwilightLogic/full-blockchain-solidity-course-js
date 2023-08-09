# Full BlockChain Solidity Learning

## Chapter #1

### Calculate Transaction Fee

Transaction Fee = ( Block Base Fee Per Gas + MaxPriorityFee Per Gas ) \* Gas Used

- Base Fee: The minimum "gas price" to send your transaction

- 1 Eth = 1000000000 GWei = 1000000000000000000 Wei

### Consensus

Consensus is the mechanism used to agree on the state of a blockchain.

#### 1. Chain Selection Algorithm

#### 2. Sybil Resistance Mechanism

- Like PoW(Proof of Work) and PoS(Proof of Stake)

## Chapter #2

### First Contract in Remix

```sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.7;

// This is a smart contract
contract SimpleStorage {
    // The basic types: boolean | unit | int | address | bytes
    // unit: POSITIVE number only

    bool hasFavoriteNumber = true;
    uint favoriteNumber = 123;
    string favoriteNumberInText = 'five';
    bytes favoriteBytes = 'cat';
}
```

> Default Value
> `uint favoriteNumber; // 0`
