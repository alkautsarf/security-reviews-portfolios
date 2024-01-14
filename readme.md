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
