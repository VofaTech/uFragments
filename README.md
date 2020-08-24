# VOFA

VOFA (code name uFragments) is a decentralized elastic supply protocol. It maintains a stable unit price by adjusting supply directly to and from wallet holders. You can read the [whitepaper](https://vofa.finance/#/whitepaper) for the motivation and a complete description of the protocol.

The official mainnet addresses are:
- ERC-20 Token: [0xD46bA6D942050d489DBd938a2C909A5d5039A161](https://etherscan.io/token/0xb5a95fcf1a3c24b0aa34ecc24cad8a1d60c1d466)
- Supply Policy: [0x1B228a749077b8e307C5856cE62Ef35d96Dca2ea](https://etherscan.io/address/0xb5a95fcf1a3c24b0aa34ecc24cad8a1d60c1d466)

## Table of Contents

- [Install](#install)
- [Testing](#testing)
- [Testnets](#testnets)
- [Contribute](#contribute)
- [License](#license)


## Install

```bash
# Install project dependencies
npm install

# Install ethereum local blockchain(s) and associated dependencies
npx setup-local-chains
```

## Testing

``` bash
# You can use the following command to start a local blockchain instance
npx start-chain [ganacheUnitTest|gethUnitTest]

# Run all unit tests
npm test

# Run unit tests in isolation
npx truffle --network ganacheUnitTest test test/unit/uFragments.js
```

## Contribute

To report bugs within this package, create an issue in this repository.
For security issues, please contact clientservice@vofa.finance.
When submitting code ensure that it is free of lint errors and has 100% test coverage.

``` bash
# Lint code
npm run lint

# View code coverage
npm run coverage
```

## License

[GNU General Public License v3.0 (c) 2018 Fragments, Inc.](./LICENSE)
