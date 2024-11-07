---
title: Unchecked Math
version: 0.8.26
description: An example of unchecked math in Solidity
keywords: [gas, unchecked, math, overflow, underflow]
cyfrinLink: https://www.cyfrin.io/glossary/unchecked-math-code-example
---

Overflow and underflow of numbers in Solidity 0.8 throw an error. This can be disabled by using `unchecked`.

Disabling overflow / underflow check saves gas.

```solidity
{{{UncheckedMath}}}
```
