# Testing Framework for Plaza

This document contains information related to the development of the testing framework for Plaza
The requirements as per <a href="https://github.com/paritytech/success_repo/issues/67">GithHub issue</a>

## Requirements

Develop and implement automated compatibility testing for web3.js and ethers.js with Westend Asset Hub's EVM-compatible smart contracts.

**Key Deliverables:**

- Test DApps for web3.js and ethers.js
- Automated test suites for both libraries

**Milestones:**

- Research and planning
- Development of test DApps
- Implementation of automated tests
- Integration and optimization

# Table of contents

1. [Research and Planning](#Research)
   1. [Planning](#Planning)
2. [Development of test DApps](#Development)
3. [Implementation of automated tests](#Testing)
4. [Integration and optimization](#Integration)

# Research

The research phase consist of conducting a market analysis of existing tooling developed by other ecosystems such that we can get inspiration for the direction of testing framework
as of now my primary focus will be getting <a href="https://book.getfoundry.sh/">Foundry</a> to work with <a href="https://github.com/paritytech/revive/tree/main">PVM</a> essentially allowing developers to compile their smartcointract using PVM
most of the work will be inspired by <a href="https://github.com/matter-labs/foundry-zksync">Foundry zksync</a>.
From the research ive done on how to adapt foundry to work with PVM ive gathered the following 
There are several parts to getting foundry to work 
- CLI
The cli portion involves having to add new CLI commands that are specific to compiling with revive or compiling to solidity compatible with the PVM
an example of how zksync has done this please see <a href="https://github.com/matter-labs/foundry-zksync/blob/main/crates/cli/src/opts/build/zksync.rs">here</a> these options are then intergrated everywhere in foundry where CLI arguments are used
see example <a href="https://github.com/matter-labs/foundry-zksync/blob/main/crates/cli/src/opts/build/mod.rs">here</a>
-  
## Planning

# Development

# Testing

# Integration
