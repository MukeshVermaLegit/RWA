RWA Creator

This project tokenizes Tesla stock (dTSLA) on-chain using smart contracts.
Users lock WETH as collateral, and the Tesla price is fetched from Alpaca and verified via Chainlink oracles.
Minting and redemption ensure every token is backed by value.

Contracts include:

dTSLA.sol – Synthetic Tesla token (collateralized minting & redemption)
sTSLA.sol – Staked dTSLA for yield or rewards
BridgedWETH.sol – Mock bridged WETH for cross-chain simulation

The project showcases how real-world assets can be fractionalized, traded, and secured on blockchain.
