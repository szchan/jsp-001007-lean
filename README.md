# JSP-001007

Lean 4 formalization of the negative answer to [Erdős problem 1202](https://www.erdosproblems.com/1202), catalogued as JSP-001007.

The target theorem is `JSP001007.not_universalHalfResidueBound` in `JSP001007/Refutation.lean`.

Mathematical credit for the negative answer belongs to Liam Price and GPT-5.4 Pro. This repository is an independent formalization of a sufficient explicit case: `ε = 1/10`, for every number of primes. It does not claim priority over earlier formalizations.

## Reproduction

Toolchain: `leanprover/lean4:v4.35.0` (`lean-toolchain`). Mathlib tag `v4.35.0`.

```sh
lake exe cache get
lake build
```

`#print axioms JSP001007.not_universalHalfResidueBound` is in `JSP001007.lean`.
