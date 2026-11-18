# Reality-Grounded, Cumulative Agency

**An integration map for studying how bounded agents acquire, realize, retain, and extend capabilities within a world that does not obey their descriptions.**

This repository is not intended to replace the underlying research repositories or assert a new universal law. Its role is to make claims, scope boundaries, dependencies, counterexamples, and executable experiments navigable.

## Central question

How can an agent embedded in a constrained world increase its effective access to viable future actions, while distinguishing *describing a possibility* from *actually realizing it*?

A useful working loop:

```text
world constraints / current organization
        |
        v
observation -> representation -> prediction / exploration
        ^                              |
        |                              v
   observed results <- lawful execution <- feasible intervention
        |                                    |
        +------ model correction <-----------+
        |
        v
stabilization / reuse / composition / institutional retention
        |
        v
changed capability frontier -> revised observations and interventions
```

This is **not** just next-step sense–model–act. It includes model-structure revision, resource limits, realization mechanisms, retention, and architecture-changing interventions. The cycle is an organizing lens, not a proof that all systems or goals share a single objective.

## Repository responsibilities

| Repository | Focus |
| --- | --- |
| [constraint_architecture](https://github.com/muritane/constraint_architecture) | Conditions and constraints on actual execution |
| [capability_systems](https://github.com/muritane/capability_systems) | Agent-relative, feasible capability composition and local realization |
| [persistent-agency-framework](https://github.com/muritane/persistent-agency-framework) | Viable futures and persistence as an organizing perspective |
| [recursive-accumulation-architecture](https://github.com/muritane/recursive-accumulation-architecture) | Retention, reuse, and cumulative layer formation |
| [recoverability-principle](https://github.com/muritane/recoverability-principle) | Viability margins and response to disturbances |
| [generative-constraint-principle](https://github.com/muritane/generative-constraint-principle) | How constraints can support stable higher-level capabilities |
| [adaptive-capability-architecture](https://github.com/muritane/adaptive-capability-architecture) | **Rust experiments** in changing capability-bearing architectures |

The links are **conceptual**, not Git submodules or code dependencies.

## How to work with the ideas

Start with [the research map](docs/research-map.md), then [the working theses](docs/working-theses.md), and [the open questions](docs/open-questions.md). For executable consequences, use the Rust crate in [adaptive-capability-architecture](https://github.com/muritane/adaptive-capability-architecture).

```sh
git clone https://github.com/muritane/adaptive-capability-architecture
cd adaptive-capability-architecture
cargo test
cargo run --example redundancy
cargo run --example execution
```

The experiments deliberately separate advertised, structurally feasible, and actually invoked capabilities. No numerical result from this toy network should be generalized to human development, real distributed systems, or autonomous AI without additional evidence.

## Research discipline

- Distinguish ontological constraints (what the world permits), epistemic models (what we believe), operational interfaces (what we can invoke), and normative criteria (what we value).
- Do not infer necessity from a component's presence, nor uselessness from a system's immediate survival after removal.
- Make explicit what conditions are held fixed when calling something "impossible", "available", or "better".
- Report migration costs, rare-event robustness, and residual model error, not just current performance.
- Prefer a falsifiable small model over another general slogan.
- Compare claims with established work in self-adaptive systems, control, network reliability, causal inference, and organizational theory.

## Status and license

Exploratory synthesis. Existing repositories retain their own scope and source histories. Content here is made available under the repository's CC BY 4.0 license.
