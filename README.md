# Charity aggregator donation contract
Create a smart contract that distributes a charity donation to a number of different charities with on-chain donation addresses.

Many charities are starting to offer direct crypto-donation addresses.

Examples:
1. [Ukraine](https://etherscan.io/address/0x165cd37b4c644c2921454429e7f9358d18a45e14)
2. [Voice's of Children (Ukraine)](https://etherscan.io/address/0xe481387CA21AeA113180a184d14B64D804027deb)
3. [Turkey earthquake donation](https://etherscan.io/address/0xCE4d5B5933B369e9c937ffCfBB9e3aeb3d2c265B)


[Here's](https://crystalblockchain.com/donation/) a list of many Ukraine related donation addresses. [Here's](https://ankarelief.org/#donation) a list of Turkey earthquake donation addresses.

## MVP Requirements
Enable a user to send a transaction containing a donation and distribute that donation in hard-coded proportions to a series of charity donation addresses.

## Stretch requirements
1. Add a feature so the user can specify which charities to donate to from a list of options.
2. Add a feature for the user to define the contribution proportions between the chosen charities.
3. Verify that the correct assets are being forwarded to the correct address.
4. (Super-stretch) Add an ability to donate on a scheduled basis (eg. once a month).