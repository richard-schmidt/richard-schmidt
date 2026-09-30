# Richard Schmidt

Product manager and AI engineer with a background in computational linguistics.
My particular strength is modelling: formalising a domain, requirements or a
specification, down to machine-checked proofs in Lean.

Site and CV: [richardschmidt.pro](https://richardschmidt.pro)

## Public projects

- [csd](https://github.com/richard-schmidt/csd): formal models of software
  architecture in Lean 4 and Mathlib. Bounded contexts, components,
  notifications and fault propagation, stated so that Lean checks their
  properties.
- [CardEngine](https://github.com/richard-schmidt/CardEngine): a rules engine
  for trading card games in Kotlin. A game is one JSON file, compiled with
  located diagnostics and played by a deterministic interpreter, with an
  Android app to author and playtest it.
- [LeanMCP](https://github.com/richard-schmidt/LeanMCP): an MCP server that
  lets a coding agent work Lean proofs against the real checker, on the
  device. Stdlib-only Python.
- [LeanWorkbench](https://github.com/richard-schmidt/LeanWorkbench): a
  phone-first Android app for writing Lean 4 proofs one tactic at a time,
  on top of LeanMCP's bridge.

These are developed in private repositories and published here as snapshots,
so their history is short.

## Writing

- [When the context map becomes a type](https://richardschmidt.pro/en/writing/context-map-notifications/):
  domain notifications as a monad, and the context map as a Lean type.
