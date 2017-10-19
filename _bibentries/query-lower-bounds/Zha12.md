---
title: How to Construct Quantum Random Functions
author: Mark Zhandry
year: 2012
pdf: "https://eprint.iacr.org/2012/182.pdf"
bibtex: "https://eprint.iacr.org/eprint-bin/cite.pl?entry=2012/182"
abbrev: Zha12
layout: bibentry
---

In the presence of a quantum adversary, there are two possible definitions of
security for a pseudorandom function. The first, which we call
standard-security, allows the adversary to be quantum, but requires queries to
the function to be classical. The second, quantum-security, allows the adversary
to query the function on a quantum superposition of inputs, thereby giving the
adversary a superposition of the values of the function at many inputs at once.
Existing proof techniques for proving the security of pseudorandom functions
fail when the adversary can make quantum queries. We give the first
quantum-security proofs for pseudorandom functions by showing that some
classical constructions of pseudorandom functions are quantum-secure. Namely, we
show that the standard constructions of pseudorandom functions from pseudorandom
generators or pseudorandom synthesizers are secure, even when the adversary can
make quantum queries. We also show that a direct construction from lattices is
quantum-secure. To prove security, we develop new tools to prove the
indistinguishability of distributions under quantum queries.

In light of these positive results, one might hope that all standard-secure
pseudorandom functions are quantum-secure. To the contrary, we show a
separation: under the assumption that standard-secure pseudorandom functions
exist, there are pseudorandom functions secure against quantum adversaries
making classical queries, but insecure once the adversary can make quantum
queries.