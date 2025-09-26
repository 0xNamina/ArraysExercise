# ArraysExercise

Array operations and timestamp filtering system with Y2K filtering functionality.

## Description

This contract demonstrates various array operations in Solidity including dynamic arrays, filtering, and efficient memory management. It features timestamp storage and filtering based on the Y2K milestone (January 1, 2000).

## Features

- **Dynamic Array Operations**: Add, reset, and manipulate number arrays
- **Timestamp Tracking**: Store timestamps with associated sender addresses
- **Y2K Filtering**: Filter timestamps after January 1, 2000 (Unix timestamp: 946702800)
- **Gas Optimization**: Efficient array operations and memory management

## Deployment Instructions

1. Open [Remix IDE](https://remix.ethereum.org/)
2. Create a new file and copy-paste the contract code
3. Compile the contract using Solidity ^0.8.0
4. Deploy on **Base Sepolia Testnet**
5. Interact with the functions:
   - `getNumbers()` - Get the current numbers array
   - `appendToNumbers(uint[] _toAppend)` - Add numbers to the array
   - `saveTimestamp(uint _unixTimestamp)` - Save a timestamp
   - `afterY2K()` - Get timestamps after Y2K
   - `resetNumbers()`, `resetSenders()`, `resetTimestamps()` - Reset arrays

## Submit Exercise

[📖 Submit Arrays Exercise](https://docs.base.org/learn/arrays/arrays-exercise)

