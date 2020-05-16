# Project: Build CryptoStar Dapp on Ethereum - Second project for Blockchain Developer course
-----
## Description
Second project for Blockchain Developer course, the intent of the project was to demonstrate learnings in creating a SmartContract using Solidity (with Truffle, Metamask, Infura and Remix). 

## Files
- [SmartContract code written in Solidity](https://github.com/marq-oh/ud-bcnd-p2/tree/master/contracts)
- [Front-end code in JavaScript and HTML (mostly provided as part of project, with the exception of the functions that had to be created for the project)](https://github.com/marq-oh/ud-bcnd-p2/tree/master/app/src)
- [Unit Tests](https://github.com/marq-oh/ud-bcnd-p2/blob/master/test/TestStarNotary.js)

## Details
|            Item           |               Value              |
|:-------------------------:|:--------------------------------:|
|     ERC-721 Token Name    |             SuperStar            |
|    ERC-721 Token Symbol   |                SS                |
|      Truffle Version      | v5.1.14-nodeLTS.0 (core: 5.1.13) |
|    OpenZeppelin Version   |              v2.3.0              |
| Solidity Compiler Version |          0.6.2 (solc-js)         |

## Other Notes
- Because I wanted to use up-to-date code, I had to modify the code that was provided to include the 'approve' function, because this is required before token can be transferred from one owner to another
- The project was also successfully deployed to the rinkeby test network. [Details can be found here](https://github.com/marq-oh/ud-bcnd-p2/blob/master/other/successful%20deployment%20to%20rinkeby.txt).