# Solidity Smart Contracts Data

This repository contains a collection of Solidity smart contracts organized by vulnerability categories. Each directory represents a specific type of security vulnerability or smart contract issue.

## Repository Structure

### Vulnerability Categories

- **access_control/** - Smart contracts demonstrating access control vulnerabilities
  - Contains contracts with issues related to improper access restrictions, unauthorized function calls, and privilege escalation

- **arithmetic/** - Contracts with arithmetic-related vulnerabilities
  - Includes integer overflow/underflow issues, unsafe arithmetic operations, and related mathematical vulnerabilities

- **bad_randomness/** - Contracts with weak or predictable randomness implementations
  - Examples of insecure random number generation and predictable randomness sources

- **denial_of_service/** - Contracts vulnerable to denial of service attacks
  - Contracts that can be exploited to cause service disruption or resource exhaustion

- **front_running/** - Contracts vulnerable to front-running attacks
  - Examples where transaction ordering can be exploited for malicious purposes

- **reentarcy/** - Contracts with reentrancy vulnerabilities
  - Classic reentrancy attack vectors and unsafe external call patterns

- **short_addresses/** - Contracts vulnerable to short address attacks
  - Examples of address validation issues and padding vulnerabilities

- **smartbug_data/** - Additional smart contract bug data
  - Collection of various smart contract vulnerabilities and bugs

- **time_manipulation/** - Contracts vulnerable to timestamp manipulation
  - Examples of time-dependent logic that can be exploited through block timestamp manipulation

- **unchecked_low_level_calls/** - Contracts with unsafe low-level call handling
  - Examples of unchecked return values from low-level calls (call, delegatecall, send, etc.)

## File Structure

Each contract directory typically contains:
- `*.sol` - Solidity source code files
- `*_metadata.json` - Contract metadata
- `cross_contract_points.json` - Cross-contract interaction analysis
- `edge_cases_failure_scenarios.json` - Edge case and failure scenario documentation
- `execution_paths_critical_program_points.json` - Critical execution path analysis
- `invariants.json` - Contract invariants documentation
- `non_vuln_tags.json` - Non-vulnerability tags
- `security_measures_exisiting_protection.json` - Existing security measures
- `temporal_conditional_information.json` - Temporal and conditional information
- `transaction_context.json` - Transaction context data

## Purpose

This dataset is intended for:
- Security researchers studying smart contract vulnerabilities
- Developers learning about common security pitfalls
- Security auditing and analysis tools
- Educational purposes in smart contract security

## Note

This repository contains vulnerable smart contracts for educational and research purposes. **Do not deploy these contracts to mainnet or any production environment.**
