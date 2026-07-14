# ChargingFoxSec

Web3 security researcher with an EVM audit background, currently expanding into Solana security, developer tooling, and open-source security engineering.

I focus on practical vulnerability analysis: proving whether an issue is exploitable, writing runnable PoCs, and separating technically valid bugs from findings that are not submit-worthy because of scope, impact, privilege assumptions, or disclosure rules.

## Current Focus

- Smart contract security review for EVM protocols
- Solana and Anchor security research, program development, and developer tooling
- Static analysis and security tooling
- PoC-backed vulnerability labs and audit methodology notes
- Open-source contributions to Web3 security projects

## Featured Work

### Web3 Vulnerability Labs

Public collection of 21 PoC-backed vulnerability labs: 14 EVM labs and 7 Soroban-oriented Rust state-machine models.

The cases preserve non-trivial reasoning patterns encountered during real audit practice while rewriting the implementation as standalone, sanitized examples. Each lab documents the vulnerable flow, exploit reasoning, mitigation, and triage boundaries.

[![Web3 Vulnerability Labs Tests](https://github.com/ChargingFoxSec/web3-vulnerability-labs/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/ChargingFoxSec/web3-vulnerability-labs/actions/workflows/tests.yml)

- 91 automated tests: 56 Foundry tests and 35 Cargo tests
- Vulnerable and fixed implementations with runnable PoCs
- EVM protocol accounting, authorization, oracle, lifecycle, and callback edge cases
- Soroban-oriented Rust state-machine models for deferred execution and configuration drift

Repository: [web3-vulnerability-labs](https://github.com/ChargingFoxSec/web3-vulnerability-labs)

### Selected Open Source Contributions

- [anza-xyz/kit#1741](https://github.com/anza-xyz/kit/pull/1741) - Fixed v0 preamble accounting in off-chain message size validation. Merged.
- [anza-xyz/kit#1770](https://github.com/anza-xyz/kit/pull/1770) - Added the missing documentation favicon reference. Merged.

### Aster Payroll

Hackathon project: a privacy-preserving payroll settlement demo on Solana.

It combines an Anchor onchain program, Token-2022 confidential-transfer concepts, a Laravel operator UI, local verification flows, and payroll receipt import logic. The project is a demo and research prototype, not a production custody protocol.

Repository: [aster-payroll](https://github.com/ChargingFoxSec/aster-payroll)

## Additional Work

- [Audit Practice Reports](https://github.com/ChargingFoxSec/my-audit-practice-reports) - Public CodeHawks First Flight reviews and other disclosed Web3 security practice reports.
- [Web3 CTF Notes](https://github.com/ChargingFoxSec/web3-ctf-notes) - Exploit notes, vulnerability patterns, and Solidity solution contracts from Web3 CTF practice.

Many real platform findings cannot be published because of disclosure rules, private scopes, or contest restrictions. I only publish reports and notes that are appropriate for public release.

## Skills

- **EVM:** Solidity, Foundry, Slither, protocol accounting, authorization boundaries, oracle and lifecycle failure modes
- **Solana:** Rust, Anchor program development, SPL Token and Token-2022 concepts, account validation patterns
- **Security:** threat modeling, exploit reproduction, PoC writing, impact triage
- **Engineering:** TypeScript, PHP/Laravel, Python, Git, Docker, GitHub Actions, test-driven debugging

## Profiles

- GitHub: [@ChargingFoxSec](https://github.com/ChargingFoxSec)
- X: [@ChargingFoxSec](https://x.com/ChargingFoxSec)
- HackenProof: [chargingfoxsec](https://hackenproof.com/hackers/chargingfoxsec)
- Sherlock: [ChargingFoxSec](https://audits.sherlock.xyz/watson/ChargingFoxSec)
- Email: [chargingfoxsec@gmail.com](mailto:chargingfoxsec@gmail.com)
