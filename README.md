# AI-Puppy-Raffle-Audit

Ai-puppy-raffle is a raffle-style smart contract that accepts ETH entries, allows participant refunds,
and selects a winner after a time delay to distribute the prize and mint an NFT, with configurable protocol fees.

# PuppyRaffle Smart Contract Audit

## Overview
This repository contains a security audit of the **ai-puppy-raffle**  smart contract.
The goal of the audit is to identify security vulnerabilities, logic flaws, and design risks.

## Summary of Findings
- High severity issues related to weak randomness
- Medium severity MEV and denial-of-service risks
- Low severity edge cases involving zero-address winners
- Informational design and configuration improvements
- Gas optimization opportunities

## Files
- `report.pdf` — Full professional audit report
- `README.md` — High-level overview of findings

## Auditor
Dharmesh PR | SecureTheChain

## Disclaimer
This audit is provided for educational and security review purposes only.
