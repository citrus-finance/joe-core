# Trader Joe

This repository contains all the contracts for Trader Joe.

## Citrus fork

This repository is based on commit [e2667042be1643b1bdb91447bb9e7383cc6798e3 / v2.4.6](https://github.com/traderjoe-xyz/joe-core/commit/e2667042be1643b1bdb91447bb9e7383cc6798e3)

We made the following changes:

- Added `feeTo` to `JoeFactory.sol` so that protocol fees are turned on automatically

## Deployed Contracts

N/A

## Setup

Make a copy of `.env.example` and rename it `.env`.

In this file, please paste in the mnemonic of your ERC-20 wallet. The other fields are optional.

Then refer to the following docs below.

## Docs

[Development](docs/DEVELOPMENT.md)

[Deployment](docs/DEPLOYMENT.md)

[MasterChefJoeV2](docs/MASTERCHEFJOEV2.md) - if your project is interested in being a double reward farm on Trader Joe!

## Security

[Security Policy](SECURITY.md)

## License

[MIT](LICENSE.txt)
