# Swisstronik Code Challenge ERC20

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.


# Introduction
### Token
```
Name   : TokenTest
Symbol : TT
```
### Smart Contract
```
0x14AAA037AcF0512df9414C71178cF1FeE3AB9607
```
### Function Mint 100 Tokens
```
function mint100tokens() public {
    _mint(msg.sender, 100*10**18);
}
```

### Explorer Minting
```
https://explorer-evm.testnet.swisstronik.com/tx/0x4b2f5248e64da82883f9e35158eea1a9e7172018515781e4ce2534edb65336e3
```

### Explorer Transfer
```
https://explorer-evm.testnet.swisstronik.com/tx/0xca4e2ed7cb5a1e2b0b143b169f0b718f797c1737ef68fa8bb419cfb0c6f5ca49
```

# Usage
```shell
npx hardhat test
npx hardhat run scripts/deploy.js
npx hardhat run scripts/mint.js
npx hardhat run scripts/transfer.js
```