# PQ Code Package

The PQ Code Package project is a new open source project that aims to build high-assurance software implementations of standards-track post-quantum cryptography algorithms.  The PQCP is a project within the [Linux Foundation](https://linuxfoundation.org/) as part of the [Post-Quantum Cryptography Alliance](https://pqca.org/).

## Initial Goals

Our initial focus in the first phase of the project will be on the [Module-Lattice-Based Key Encapsulation Mechanism (ML-KEM) algorithm](https://csrc.nist.gov/pubs/fips/203/ipd).  As the project grows, we intend to also produce implementations for [ML-DSA](https://csrc.nist.gov/pubs/fips/204/ipd) and [SLH-DSA](https://csrc.nist.gov/pubs/fips/205/ipd), as well as other standards-track post-quantum algorithms.

We aim for implementations produced by the project to have assurances given either as a result of external audits or as a result of formal verification methods (or both).

We have interest from early participants to create or build on existing implementations for the following algorithms and platforms, and hope to expand this list as the project progresses:

- a platform-independent implementation of ML-KEM in C
- an AVX2-optimized assembly implementation of ML-KEM
- a Rust implementation of ML-KEM
- an aarch64-optimized implementation of ML-KEM

## Recent progress

Following the [March 2024 Hackathon](https://hackathon.pqcodepackage.org/202404/2024-04-hackathon.html) implementation code is starting to be added.

An initial [documentation site](https://docs.pqcodepackage.org) is also being built

[TSC meetings](https://github.com/pq-code-package/tsc/blob/main/meetings/index.md) are now underway, and are open to anyone to join. [Voting members and lead](https://github.com/pq-code-package/tsc/blob/main/members/index.md) have been elected. Meetings are being held every two weeks on a Thursday at 1300 UTC. See the [PQCA calendar](https://pqca.org/calendar/)

Some of the current issues we're thinking about include
 - How we document and explain [assurance](https://github.com/pq-code-package/tsc/issues/3)
 - Agreement on a [common API](https://github.com/pq-code-package/tsc/issues/4)

## Getting Involved

Our [docs site](https://docs.pqcodepackage.org/latest/contributing/asking-a-question/) has the best link to the list of chat and email options for engaging in discussions with the community - in addition to issues in our [repositories](https://docs.pqcodepackage.org/latest/contributing/repositories/). [TSC issues](https://github.com/pq-code-package/tsc/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc) track cross-project concerns.


The best way right now to indicate your interest in helping with the project and staying up-to-date on progress is to follow the pq-code-package organization on GitHub and to say hello on the [#pqcp-general channel](https://discordapp.com/channels/1202723482224295936/1203396039977996359) on [our Discord server](https://discord.gg/qRfMantKwc).
