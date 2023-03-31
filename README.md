# HealthDrive Account Abstraction Grant Proposal Outline
## Project Abstract

HealthDrive is an open protocol for secure medical data storage and transmission that aims to collect a person's medical records in their personal wallet, promoting self-custody and greater control over their medical information. The project aims to leverage Account Abstraction for mass adoption, with a focus on user-friendly registration processes and long-term data persistence.

## Objectives

- Develop a Paymaster frontend for ecosystem partners to subsidize gas fees.
- Create a wallet guardian system to ensure long-term persistence and recoverability of medical records.
- Promote mass adoption of HealthDrive by creating a seamless user experience.

## Outcomes

This project benefits the greater Ethereum ecosystem by providing a secure and decentralized solution for medical data storage and transmission, encouraging the adoption of blockchain technology in the healthcare industry. Additionally, the open-source nature of the project allows other projects (even non-healthcare related) with similar data persistence requirements to utilize our solution.

## Grant Scope

HealthDrive is developing features tailored for ecosystem partners, such as insurance companies, pharma companies, medical hardware manufacturers, and hospitals/individual doctors, to foster platform adoption and improve usability.

### Paymaster frontend development:
- Design a dApp for ecosystem partners to subsidize gas fees for HealthDrive Wallet users (patients).
- Create an intuitive system to manage rules and restrictions for transaction subsidies.
- Implement and optimize the dApp for seamless ecosystem partner integration. 


### Wallet guardians:
  - Develop a dApp for ecosystem partners to fulfill their Guardian role: accept guardianship over new patients and respond to ownership transfer requests to new addresses.
  - Integrate the "Wallet Guardian" feature into HealthDrive Wallet, allowing users to grant or revoke consent for selected partners as Guardians and view their current guardians.
  - Implement the dApp, ensuring security and ease of use for ecosystem partners.


### Educational content:
  - Produce comprehensive educational resources explaining HealthDrive's inner workings and the role of Account Abstraction for both ecosystem partners and patients.
  - Develop content in various formats, such as articles, videos, and infographics, to cater to different use cases.

By concentrating on these aspects, HealthDrive aims to deliver an accessible, secure solution for decentralized medical data storage and transmission, encouraging widespread adoption and enhancing user experience for both individuals and ecosystem partners.

## Project Team

The project team consists of three members:

- Web3 Developer: Full-stack developer with expertise in React and Solidity, responsible for designing, implementing, and optimizing the dApps and wallet features - 80 hours per month for 5 months. Some of the more mundane work like frontend development using provided mockups will be outsourced.
- Security Expert (external): Ensuring the security and privacy of the apps, conducting audits, and providing guidance on best practices for secure development. Currently there are two candidates for this role.
- UI/UX designer (external).

## Background

Alexander Potapov [github.com/alpotapov](https://github.com/alpotapov):
- 5 years of corporate experience as a full-stack software developer.
- Winner of ETHGlobal HackFS hackathon and receiver of IPFS dev grant.
- 25+ hackathons over the span of the last 10 years.


## Methodology

1. Requirement Engineering: Identify the specific needs of ecosystem partners and patients that the apps will cover.
1. MVP Development: Create an MVP for both the Paymaster frontend and Wallet Guardian feature, implementing the core functionality first.
1. Security Audits: Conduct security audits after developing MVPs to ensure the core functionality is working as expected.
1. Iterative development: Improve and refine MVPs to make them production-ready.

## Timeline

Month 1:

- Develop a Minimum Viable Product (MVP) for the Paymaster frontend, enabling partner to top up their balance and allow patient to complete a subsidized transaction through the HealthDrive Wallet.

Month 2:

- Create an MVP for the Wallet Guardian feature, showcasing the process of designating an ecosystem partner as a guardian and restoring access to the wallet.
- Conduct a security audit of the Paymaster system.

Month 3:

- Refine the Paymaster frontend, transforming the MVP into a fully-functional, user-friendly product.
- Perform a security audit of the Wallet Guardian system.

Month 4:

- Enhance the Wallet Guardian frontend and optimize its performance.
- Implement additional screens in the HealthDrive Wallet for enabling the Guardians feature.
- Initiate content creation for educational purposes.

Month 5:

- Carry out a final security audit of the entire system.
- Conduct comprehensive testing of all platform features.
- Allocate time for addressing any outstanding development issues or concerns.

## Budget

Requested grant amount: $50,000

Budget breakdown:

- Web3 Developer Costs: $30,000 (includes hiring freelance developer for assistance)
- Security Expert Costs: $10,000 (3 audits)
- Freelance UI/UX Designer: $5,000
- Miscellaneous Costs: $5,000 (collaboration tools subscriptions, contingency, unforeseen expenses)


