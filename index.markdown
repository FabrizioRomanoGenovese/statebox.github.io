---
layout: team
title: "- Compositional Diagrammatic Programming Language"
peeps:
  team:
    - github: difranco
      name: Anthony Di Franco
    - github: FabrizioRomanoGenovese
      name: Fabrizio Romano Genovese
    - github: wires
      name: Jelle Herold
    - github: antonleviathan
      name: Anton Livaja
    - github: epost
      name: Erik Post
    - github: bertspaan
      name: Bert Spaan
    - web: http://math.mit.edu/~dspivak/
      name: David Spivak (advisor)
---

## Compositional Diagrammatic Protocol Language

Statebox is a radically different way to build smart contracts, inspired
by modern physics and mathematics.

Instead of text-based instructions telling a smart contract how to
achieve certain behaviour, statebox contracts are represented as
diagrams.

End-to-end correctness proofs are a fundamental design principle, not an
afterthought: the core is a mathematically minimalistic structure, aimed
to facilitate reasoning about its behaviour.

As a result, diagrams can be composed into bigger diagrams, preserving
their properties, such as termination guarantees.

This way contracts become easier to understand, build and inspect.

## Some WIP

- [nll-spec](https://github.com/statebox/nll-spec) *binary encoding* for list of lists of (signed) varints
- [nll-js](https://github.com/statebox/nll-js) JS implementation of NLL
- [ipfs/notes#168](https://github.com/ipfs/notes/issues/168) proposal for binary encoding of bipartite graphs
