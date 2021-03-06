# Bunched logic

https://en.wikipedia.org/wiki/Bunched_logic

**Bunched logic**, a variety of [substructural logic](./substructural-logic.md) (proposed by Peter O'Hearn and David Pym), provides primitives for reasoning about resource composition, thus helping with compositional analysis of computer systems.

It has category-theoretic and truth-functional semantics which can be understood in terms of an abstract concept of resource, and a proof theory in which the contexts Γ in an entailment judgement Γ ⊢ A are tree-like structures called bunches (rather than lists, multisets or sets, as in most proof calculi).

Bunched logic has an associated type theory, and its first application was in providing a way to control the aliasing and other forms of interference in imperative programs.

The logic has seen further applications in program verification, where it is the basis of the assertion language of [separation logic](./separation-logic.md), and in [systems modelling](), where it provides a way to decompose the resources used by components of a system.
