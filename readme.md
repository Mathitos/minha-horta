## Index
- [Considerations](#considerations)
- [Supported Commands](#supported-commands)


### Considerations
- To run tests and debug Solidity code without dealing with live environments we use [Hardhat](https://hardhat.org/)
- Initial Setup as made following [Oliver Jumpertz article](https://blog.oliverjumpertz.dev/how-to-set-up-a-solidity-project-and-create-your-first-smart-contract)


### Supported Commands
To fetch project dependencies(is necessary to run this before any other commands)
```$ yarn```

To start a local etherium network
```$ yarn local-testnet```

To Deploy your contract to your local network
```$ yarn deploy:local```

To run our tests for our contract
```$ yarn test```

To simply build our contract binaries
```$ yarn compile```
