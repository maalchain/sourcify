# Changelog for `sourcify-server`

All notable changes to this project will be documented in this file.

## [sourcify-server@1.3.1] - 2023-11-23

- Add AWS_LAMBDA_FUNCTION to specify the name of the lambda fucntion

## [sourcify-server@1.3.0] - 2023-11-23

- Use compiler as a lambda function
- Custom compiler using SOLIDITY_COMPILER env variable: `local`, `lambda`
- Run tests in parallel
- New chains:
  - Coredao testnet chain (1115)
  - Rootstock (30)
  - Zora Sepolia Testnet (999999999)

## [sourcify-server@1.2.0] - 2023-11-03

- Add support for the Verifier Alliance (disabled)
- Move server under ./services in the monorepo
- Refactor contract creation transaction fetcher
- Minor fixes

## [sourcify-server@1.1.2] - 2023-10-19

- Add a filter to prevent the same contract to be verified simultaneously

## [sourcify-server@1.1.1] - 2023-10-09

- Remove monitor code from the server directory `src/`
- Update chains.json
- Renaming `ALCHEMY_ID` and `INFURA_ID` to `..._API_KEY`
- Remove the `monitored` field from `sourcify-chains.ts`
- New chains:
  - Ethereum Holesky Testnet (17000)
  - PulseChain Mainnet (369)
  - Mind Smart Chain Mainnet (9996)
  - Mind Smart Chain Testnet (9977)
  - Shrapnel Testnet (2038)
  - Shrapnel Subnet (2044)
  - Arthera Testnet (10243)
  - Core Blockchain Mainnet (1116)
  - Q Mainnet (35441)
  - Q Testnet (35443)

## [sourcify-server@1.1.0] - 2023-09-04

- Updated lerna to `7.1.5`
- #1158 Add `REPOSITORY_URL_HOST` env variable to `sourcify-server` to allow for custom repository paths in containers. Previously this was hardcoded as `../../data/repository`
- Updates chains.json
- New chains:
  - Kiwi Subnet (2037)
  - Beam Subnet (4337)
  - Amplify Subnet (78430)
  - Bulletin Subnet (78431)
  - Conduit Subnet (78432)

## Older releases

Previously, the releases were not done one separate modules of Sourcify but for the repository as a whole.
You can find the changelog for those releases in [older releases](https://github.com/ethereum/sourcify/releases) for this repository.
