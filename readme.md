# Security Reviews Portfolio

## Table of Contents

- [Security Reviews Portfolio](#security-reviews-portfolio)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Methodology](#methodology)
  - [Projects](#projects)
    - [Password Store](#password-store)
    - [Puppy Raffle](#puppy-raffle)
    - [T-Swap](#t-swap)
    - [Thunder Loan](#thunder-loan)
    - [Boss Bridge](#boss-bridge)

## Overview

This repository showcases a collection of smart contract security reviews that I have conducted. As a blockchain and smart contract security researcher, I have thoroughly analyzed and audited various smart contracts to ensure they meet the highest standards of security.

## Methodology

My smart contract security reviews follow a comprehensive methodology, including the following steps:

1. **Scoping:** Clearly defining the scope of the smart contract security review, including the specific components, functionalities, and interactions to be assessed.
2. **Static Analysis:** Employing static analysis tools to scan the code for known security patterns and vulnerabilities.
3. **Reconnaissance:** Conducting initial reconnaissance to gather information about the smart contract, its dependencies, and any relevant external factors that may impact security.

4. **Vulnerability Identification:** Identifying and assessing potential vulnerabilities in the smart contract code through a combination of manual code review, static analysis, and dynamic analysis.

5. **Reporting:** Compiling detailed reports that highlight the findings, analysis, and recommendations based on the identified vulnerabilities. These reports serve as comprehensive documentation for developers and stakeholders.

## Projects

### [Password Store](2024-01-06-passwordstore-audit-reports.pdf)

- **Description:** PasswordStore is a protocol dedicated to storage and retrieval of a user’s passwords. The protocol is
  designed to be used by a single user, and is not designed to be used by multiple users. Only the owner should be able to set and access this password.
- **Date of Review:** 01/06/2024
<!-- - **Key Findings:** Summarize the main security findings and recommendations. -->

### [Puppy Raffle](2024-01-10-puppy-raffle-audit.pdf)

- **Description:** Puppy Rafle is a protocol dedicated to raffling off puppy NFTs with variying rarities. A portion of entrance fees go to the winner, and a fee is taken by another address decided by the protocol owner.
- **Date of Review:** 01/10/2024
<!-- - **Key Findings:** Summarize the main security findings and recommendations. -->

### [T-Swap](2024-01-14-t-swap-audit.pdf)

- **Description:** TSWAP is an constant-product AMM that allows users permissionlessly trade WETH and any other
  ERC20 token set during deployment. Users can trade without restrictions, just paying a tiny fee in each
  swapping operation. Fees are earned by liquidity providers, who can deposit and withdraw liquidity at
  any time.
- **Date of Review:** 01/14/2024
<!-- - **Key Findings:** Summarize the main security findings and recommendations. -->

### [Thunder Loan](2024-01-17-thunder-loan-audit-reports.pdf)

- **Description:** The ThunderLoan protocol is meant to do the following:
1. Give users a way to create flash loans
2. Give liquidity providers a way to earn money off their capital
- **Date of Review:** 01/17/2024
<!-- - **Key Findings:** Summarize the main security findings and recommendations. -->

### [Boss Bridge](2024-01-18-boss-bridge-audit-reports.pdf)

- **Description:** The Boss Bridge is a bridging mechanism to move an ERC20 token (the “Boss Bridge Token” or “BBT”)
from L1 to an L2 the development team claims to be building. Because the L2 part of the bridge is
under construction, it was not included in the reviewed codebase.
The bridge is intended to allow users to deposit tokens, which are to be held in a vault contract on L1.
Successful deposits should trigger an event that an off-chain mechanism is in charge of detecting to
mint the corresponding tokens on the L2 side of the bridge.
Withdrawals must be approved operators (or “signers”). Essentially they are expected to be one or more
off-chain services where users request withdrawals, and that should verify requests before signing the
data users must use to withdraw their tokens. It’s worth highlighting that there’s little-to-no on-chain
mechanism to verify withdrawals, other than the operator’s signature. So the Boss Bridge heavily relies
on having robust, reliable and always available operators to approve withdrawals. Any rogue operator
or compromised signing key may put at risk the entire protocol.
- **Date of Review:** 01/18/2024
<!-- - **Key Findings:** Summarize the main security findings and recommendations. -->
