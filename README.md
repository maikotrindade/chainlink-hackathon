# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

### Get started

Install hardhat
`npm install --save-dev hardhat`

Export your [private key](https://metamask.zendesk.com/hc/en-us/articles/360015289632-How-to-Export-an-Account-Private-Key) and get Alchemy API key on `Kovan` (testnet with faucet system currently working and compatible with Keepers).
Create `.env` file with the following properties:

```
ALCHEMY_API_KEY = XXXXXXXXXX
PRIVATE_KEY = XXXXXXXX
```

1. npx hardhat node
2. npx hardhat run scripts/deploy.js --network kovan

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

### Test coverage

`npx hardhat coverage`

### Deploy

`npx hardhat run scripts/deploy.js --network kovan`
