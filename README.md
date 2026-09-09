# ChargingFoxSec

Web3 security researcher and open-source engineer working across EVM, Solana, and developer tooling.

I turn protocol and tooling issues into reproducible engineering evidence: runnable PoCs, regression tests, and focused upstream fixes. My work covers EVM security review, Solana and Anchor development, and static-analysis infrastructure.

Open to Web3 security engineering, protocol engineering, and developer tooling roles.

## Current Focus

- EVM protocol and smart contract security review
- Solana and Anchor program development and security research
- Static analysis, fuzzing, and developer tooling
- PoC-backed vulnerability labs and audit methodology notes
- Open-source issue reproduction, regression testing, and upstream fixes

## Featured Work

### Web3 Vulnerability Labs

Public collection of 20+ PoC-backed labs covering Web3 vulnerability patterns across EVM and Soroban-oriented Rust state-machine models.

The cases preserve non-trivial reasoning patterns encountered during real audit practice while rewriting the implementation as standalone, sanitized examples. Each lab documents the vulnerable flow, exploit reasoning, mitigation, and triage boundaries.

[![Web3 Vulnerability Labs Tests](https://github.com/ChargingFoxSec/web3-vulnerability-labs/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/ChargingFoxSec/web3-vulnerability-labs/actions/workflows/tests.yml)

- 90+ automated tests across Foundry and Cargo
- Vulnerable and fixed implementations with runnable PoCs
- EVM protocol accounting, authorization, oracle, lifecycle, and callback edge cases
- Soroban-oriented Rust state-machine models for deferred execution and configuration drift

Repository: [web3-vulnerability-labs](https://github.com/ChargingFoxSec/web3-vulnerability-labs)

### Selected Security Results

- [HackenProof](https://hackenproof.com/hackers/chargingfoxsec) - Paid findings across Critical, High, and Medium severities.
- [Sherlock](https://audits.sherlock.xyz/watson/ChargingFoxSec) - A validated Medium-severity finding.

### Selected Open Source Contributions

- [crytic/medusa#840](https://github.com/crytic/medusa/pull/840) - Kept Slither diagnostics separate from machine-readable JSON output and added regression coverage. Merged.
- [anza-xyz/kit#1748](https://github.com/anza-xyz/kit/pull/1748) - Prevented JavaScript protocol hooks from being dispatched as RPC methods and added Node and browser regression coverage. Merged.
- [anza-xyz/kit#1741](https://github.com/anza-xyz/kit/pull/1741) - Fixed v0 message preamble accounting in off-chain message size validation. Merged.

### Aster Payroll

Hackathon prototype exploring privacy-preserving payroll settlement on Solana.

It combines an Anchor onchain program, Token-2022 confidential-transfer concepts, a Laravel operator UI, local verification flows, and payroll receipt import logic. The project is a demo and research prototype, not a production custody protocol.

Repository: [aster-payroll](https://github.com/ChargingFoxSec/aster-payroll)

## Skills

- **EVM:** Solidity, Foundry, Slither, fuzzing and invariant testing
- **Solana:** Rust, Anchor program development, SPL Token and Token-2022 concepts, account validation patterns
- **Security:** protocol accounting, authorization boundaries, oracle and lifecycle failure modes, exploit reproduction, impact triage
- **Engineering:** Go, TypeScript, PHP/Laravel, Python, Git, Docker, GitHub Actions, test-driven debugging

## Profiles

- GitHub: [@ChargingFoxSec](https://github.com/ChargingFoxSec)
- X: [@ChargingFoxSec](https://x.com/ChargingFoxSec)
- HackenProof: [chargingfoxsec](https://hackenproof.com/hackers/chargingfoxsec)
- Sherlock: [ChargingFoxSec](https://audits.sherlock.xyz/watson/ChargingFoxSec)
- Email: [chargingfoxsec@gmail.com](mailto:chargingfoxsec@gmail.com)
