---
title: Delegatecall
version: 0.8.26
description: Example of how to use delegatecall in Solidity
keywords: [delegatecall, call, contract, contracts, function, functions]
cyfrinLink: https://www.cyfrin.io/glossary/delegatecall-solidity-code-example
---

`delegatecall` is a low level function similar to `call`.

When contract `A` executes `delegatecall` to contract `B`, `B`'s code is executed

with contract `A`'s storage, `msg.sender` and `msg.value`.

```solidity
{{{Delegatecall}}}
```
