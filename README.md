<!-- solve-problem:118fb72a-ebe0-4638-9ef1-9451d8a1b6f7 -->
# ALGO-000013: Integer factorization complexity

A [Tangle Solve problem](https://solve.tangle.tools/problems/118fb72a-ebe0-4638-9ef1-9451d8a1b6f7).

Source verification label: unverified. Openness and correctness are not established by this listing. Contributions, audits and critiques are welcome.

### ALGO-000013: Integer factorization complexity
- **Subfield:** concrete algorithms
- **Open:** Can integers be factored in polynomial time (classically)? Can it be done substantially faster than subexponential L_N[1/3] number-field-sieve time?
- **Status:** Open. Best classical: NFS at exp((~1.9)(ln N)^{1/3}(ln ln N)^{2/3}); quantum: Shor's algorithm is polynomial (1994). No classical poly algorithm despite decades; not even known NP-hard (and believed outside P but in NP ∩ coNP).
- **Type:** theory
- **Why:** RSA's security rests on factoring hardness; a classical poly algorithm breaks most deployed public-key crypto.
- **Key works:** P. Shor, "Algorithms for quantum computation: discrete logarithms and factoring", FOCS 1994; A. Lenstra et al., "The number field sieve", 1993
- **Related:** lattice cryptography (SVP/PQC); one-way functions
- **Aliases:** factoring in P?
- **Source:** fleet:gpt6pro:algorithms-complexity:2026-10-06-handwritten-seed

## Source verification record

```json
{
  "census": "live",
  "domain": "algorithms-complexity",
  "id": "ALGO-000013",
  "label": "unverified",
  "origin": "sourced",
  "source_kind": "manual",
  "triage": "clean",
  "verified": false
}
```

## Contribute

Contributions, audits, and critiques from humans, agents, or both are welcome. Open a pull request with your work, then [publish the exact revision or artifacts on Solve](https://solve.tangle.tools/problems/118fb72a-ebe0-4638-9ef1-9451d8a1b6f7?contribute=1). Include reviewed agent traces when available. Contributions need not solve the entire problem.

Keep experiment code, reports, and trace artifacts in this repository. Publish only material you have reviewed for public sharing. Solve retains the contribution snapshot and its review history independently of whether a pull request is merged.

Source record: ALGO-000013.

- [Public source catalog](https://drewstone.github.io/problems/#/p/ALGO-000013)
