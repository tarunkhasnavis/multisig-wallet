# Multi-signature Wallet for Ethereum

This wallet requires some m-of-n quorum of approved private keys to approve a transaction before it is executed.This multisignature wallet is implemented as a smart contract on Ethereum where each of the approved external accounts sends a transaction to in order to "sign" a group transaction.

The contract will have multiple owners that will determine which transactions the contract is allowed to execute. Contract owners need to be able to propose transactions that other owners can either confirm or revoke. If a proposed transaction receives enough support, it will be executed.
