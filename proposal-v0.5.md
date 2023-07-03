# Ask! v0.5 Proposal & Report

Due to the [breaking changes] of `pallet-contracts` and the limitations of [Assemblyscript](https://github.com/AssemblyScript/assemblyscript),
we have no way to be compatible with the latest version of pallet-contracts.

[breaking changes]: https://github.com/paritytech/substrate/issues/13621

In order to apply some new features and code optimizations we have developed in recent months as early as possible,
we intend to release a new version v0.5, although this version is not compatible with the latest pallet-contracts version.

The `Ask!` v0.5 mainly includes four parts:

1. Dependency update
2. Refactoring and optimization of the [(de)serialization library](https://github.com/ask-lang/serde-as).
3. Update contract runtime and host functions to be compatible with [polkadot-v0.9.39](https://github.com/paritytech/substrate/tree/polkadot-v0.9.39).
4. Update documentations to add more details of `Ask!`.

## Dependency update

- [assemblyscript](https://github.com/AssemblyScript/assemblyscript):
- [vistor-as](https://github.com/as-pect/visitor-as):
- [serde-as libraries](https://github.com/ask-lang/serde-as):

## Serialization/Deserialization libraries

- as-serde:
- as-serde-scale:
- as-serde-json:
- as-serde-transform:

## Contract runtime and host functions

## Documentation
