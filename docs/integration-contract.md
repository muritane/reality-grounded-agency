# Integration contract with experimental repositories

This repository intentionally contains **no duplicate Rust implementation**.

The experimental API is maintained in [adaptive-capability-architecture](https://github.com/muritane/adaptive-capability-architecture) under its Rust crate name `adaptive-capability-architecture` (import path `adaptive_capability_architecture`).

The following levels must not be conflated:

| Layer | Evidence expected |
| --- | --- |
| Represented | A label or proposition exists in a model |
| Structurally feasible | Graph dependencies, accessible providers, and budgets pass explicit checks |
| Invocable | A matching runtime handler exists and can be called |
| Successful | The handler performs the operation and the intended external postcondition is observed |
| Reusable | The operation remains available across relevant conditions and repetitions |

Current tests cover mainly the middle levels and a simple in-process handler. They do **not** certify external postconditions, real robotics systems, live cloud infrastructure, or self-improving agents.

Protocol for integrating new experiments:

1. State a proposition and its counterexample.
2. Specify modeled state, decisions, resources, and observables.
3. Give an executable entry point and deterministic baseline.
4. Report assumptions that make the result possible.
5. Link results here without copying the experiment implementation.
