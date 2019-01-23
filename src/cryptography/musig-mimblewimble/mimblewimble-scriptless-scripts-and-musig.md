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

