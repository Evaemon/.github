# Evaemon

> *Security that assumes nothing. Systems that prove everything.*

## What We Build

Evaemon develops **post-quantum security infrastructure** — tools and frameworks designed to protect systems, data, and communications against both current and future threats.

We operate at the intersection of **cryptography**, **process isolation**, and **system integrity**, building security solutions that are:

- **Quantum-resilient** — engineered to withstand attacks from both classical and quantum computers
- **Deterministic** — every decision is traceable, every action is verifiable
- **Structurally secure** — security enforced through architecture, not configuration
- **Zero-trust by design** — nothing is assumed safe until proven

## Our Approach

Traditional security is built on assumptions. Assumptions about which algorithms are safe. Assumptions that the host is trustworthy. Assumptions that keys won't be stolen. Assumptions that logs haven't been tampered with.

Evaemon eliminates assumptions.

We build systems where security properties are **provable, not presumed**. Where access is binary — granted or denied, with no grey area. Where every event is recorded in tamper-evident chains that prove not only what happened, but that nothing was changed after the fact.

Our tools are designed to work **independently or as a unified stack**, giving organizations the flexibility to adopt what they need while maintaining the option to integrate deeper over time.

## Principles

**Black or white.** Access is granted or denied. The host is clean or compromised. The seal is intact or broken. We do not operate in grey areas — grey areas are where attackers live.

**Prove, don't promise.** Any system can claim to be secure. Evaemon systems produce cryptographic evidence of their integrity. Trust is not requested — it is demonstrated.

**Built for what's coming.** Quantum computing will break most of today's cryptography. We build for that reality now, not when it arrives. Our hybrid approach ensures protection today while preparing for tomorrow.

**Architecture over policy.** Policies can be changed. Architecture cannot be bypassed. We enforce security through structural boundaries, not rules that can be overridden.

**Universal by design.** Security is not a regional problem. Our tools are built to serve any organization, in any industry, anywhere in the world.

## Who It's For

Evaemon tools are built for organizations and engineers who:

- Need to protect sensitive assets with provable integrity
- Are preparing for the post-quantum cryptography migration
- Require tamper-evident audit trails for compliance or accountability
- Want security guarantees enforced by architecture, not trust
- Operate in environments where failure is not an option

This includes — but is not limited to — healthcare, finance, government, defense, critical infrastructure, and any organization that handles data worth protecting.

## The Stack

Evaemon is not a single product. It is a growing ecosystem of security tools, each solving a specific problem, each usable standalone, and each stronger when combined. Our repositories reflect this modular philosophy — explore them to see what's available and what's in development.

## Standing on the Shoulders of Giants

Evaemon exists because of the groundbreaking work done by the open-source and research communities. We build on top of their foundations, and we believe in giving credit where it is earned.

- **[Open Quantum Safe (OQS)](https://openquantumsafe.org/)** — The pioneering open-source project for post-quantum cryptographic algorithms. OQS and their liboqs library are the bedrock that makes practical post-quantum cryptography possible. Without their work, Evaemon would not exist.
- **[Post-Quantum Cryptography Alliance (PQCA)](https://pqca.org/)** — Part of the Linux Foundation, driving the collaborative effort to transition the world to quantum-resistant cryptography.
- **[NIST Post-Quantum Cryptography Project](https://csrc.nist.gov/projects/post-quantum-cryptography)** — The standardization effort that evaluated, tested, and selected the algorithms (ML-KEM, ML-DSA, SLH-DSA) that form the cryptographic core of our work.
- **[OpenSSH](https://www.openssh.com/)** — The foundation of secure remote access that has protected systems for over two decades.
- **[The Linux Kernel](https://kernel.org/)** — The operating system that powers our infrastructure and provides the security primitives (namespaces, seccomp, IMA, TPM integration) that make our isolation architecture possible.
- **[Postfix](https://www.postfix.org/)** — Wietse Venema's masterwork in security-through-architecture. The Postfix privilege separation model directly inspired our approach to process isolation.

We are grateful to every contributor, researcher, and maintainer in these communities. Open source moves the world forward, and we are proud to build on that legacy.

## Part of Trednets

Evaemon is developed by **[Trednets](https://trednets.com/)** as part of a broader technology ecosystem focused on deterministic, traceable, and resilient systems.

---

*Every connection is verified. Every decision is traceable. Every event is provable.*
