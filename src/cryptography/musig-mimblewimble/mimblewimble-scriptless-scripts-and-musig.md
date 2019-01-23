# Mimblewimble, Scriptless Scripts and MuSig 

## Abstract

Interactive signature aggregation where each signer signs their own message will be a corner stone for smart contract integration into the Mimblewimble. This report investigates the basic constructs needed for such an implementation.

## Contents 

- [Mimblewimble, Scriptless Scripts and MuSig](#mimblewimble,-scriptless-scripts-andmusig)

- [Abstract](#abstract)

  - [Contents](#contents)
  - [Introduction](#introduction)
    - [Recap of Mimblewimble](#introduction-to-mimblewimble)
    - [Recap of scriptless scripts in Mimblewimble](#recap-of-scriptless-scripts-in-mimblewimble)
    - [Recap of Musig](#recap-of-musig)
  - [How scriptless scripts are used in Mimblewimble](#how-scriptless-scripts-are-used-in-mimblewimble)

  - [How scriptless scripts are proposed for MuSig](#how-scriptless-scripts-are-proposed-for-musig)
  - [The need for smart contracts for Tari](#the-need-for-smart-contracts-for-tari)
    - [MuSig base layer contracts](#musig-base-layer-contracts)
  - [How MuSig can be used in Mimblewimble to achieve the goal of contracting for Tari](#how-musig-can-be-used-in-mimblewimble-to-achieve-the-goal-of-contracting-for-tari) 
  - [Conclusions, observations and recommendations](#conclusions,-observations-and-recommendations)
  - [Contributors](#contributors) 

## Introduction

### Recap of Mimblewimble

[Mimblewimble](../../protocols/mimblewimble-1/sources/PITCHME.link.md) is a blockchain format and protocol that provides extremely good scalability, privacy and fungibility by relying on strong cryptogrtphic primitives. The protocol designed for confidential transactions. The essence is that a Pedersen Commitment to $ 0 $ can be viewed as an Elliptic Curve Digital Signature Algorithm (ECDSA) public key, and that for a valid confidential transaction the difference between outputs, inputs, and transaction fees must be $ 0 $. A *prover* constructing a confidential transaction can therefore sign the transaction with the difference of the outputs and inputs as the public key. This enables a greatly simplified blockchain in which all spent transactions can be pruned, and new nodes can efficiently validate the entire blockchain without downloading any old and spent transactions. The blockchain consists only of block-headers, remaining Unspent Transaction Outputs (UTXO) with their range proofs and an unprunable transaction kernel per transaction. Mimblewimble also allows transactions to be aggregated before being committed to the blockchain. ([[1]], [[2]])

### Recap of scriptless scripts in Mimblewimble

### Recap of scriptless scripts in Mimblewimble 

### Recap of MuSig 

## How scriptless scripts are proposed for MuSig

## The need for smart contracts for Tari 

### MuSig base layer contracts 

## How MuSig can be used in Mimblewimble to achieve the goal of contracting for Tari 

## Conclusions, observations and recommendations 

## Contributors 

## References 

[[1]] Bulletproofs: Short Proofs for Confidential Transactions and More, Blockchain Protocol Analysis and Security Engineering 2018, Bünz B. et al., http://web.stanford.edu/~buenz/pubs/bulletproofs.pdf, Date accessed: 2018-09-18.

[1]: http://web.stanford.edu/~buenz/pubs/bulletproofs.pdf
"Bulletproofs: Short Proofs for Confidential Transactions 
and More, Blockchain Protocol Analysis and Security 
Engineering 2018, 
Bünz B. et al"

[[2]] Mimblewimble Explained, https://www.weusecoins.com/mimble-wimble-andrew-poelstra/, Date accessed: 2018-09-10.

[2]: https://www.weusecoins.com/mimble-wimble-andrew-poelstra
"Mimblewimble Explained"

