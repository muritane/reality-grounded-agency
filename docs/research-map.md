# Research map: problems, not a ranking of abstractions

## 1. Constraints and realization

The environment is not obliged to obey a symbolic plan. A description, goal, compiler output, or declared service is not itself a physical transition. Ask: where is execution occurring, with which resources, binding mechanism, and failure surface?

Primary work: [constraint_architecture](https://github.com/muritane/constraint_architecture), [realization_constraint.md](https://github.com/muritane/capability_systems/blob/main/realization_constraint.md), [executability-filter](https://github.com/muritane/executability-filter).

## 2. Capability as relation

Capability is not a free-floating inventory score. It is conditional on embodiment, information, resource access, interfaces, authority, topology, and context. Agent-relative feasible composition is narrower than syntactic combination.

Primary work: [capability_systems](https://github.com/muritane/capability_systems), [from_action_labels_to_adaptive_operator_refinement.md](https://github.com/muritane/capability_systems/blob/main/from_action_labels_to_adaptive_operator_refinement.md).

## 3. Learning and representation

Updating values inside a fixed coordinate system differs from changing the distinctions or coordinate system itself. Unexpected residuals can justify refining categories, adding variables, or changing the model architecture.

Primary work: [from_fixed_categories_to_mutable_frames.md](https://github.com/muritane/capability_systems/blob/main/from_fixed_categories_to_mutable_frames.md), [from_primitive_distinction_to_self_refining_representation.md](https://github.com/muritane/capability_systems/blob/main/from_primitive_distinction_to_self_refining_representation.md).

## 4. Continuation, recoverability, and accumulation

Success now can trade against available options later. Retained discoveries, tools, institutions, and infrastructure may widen future feasible trajectories. Viability is one research objective, not a logically necessary terminal value for all agents.

Primary work: [persistent-agency-framework](https://github.com/muritane/persistent-agency-framework), [recoverability-principle](https://github.com/muritane/recoverability-principle), [recursive-accumulation-architecture](https://github.com/muritane/recursive-accumulation-architecture).

## 5. Reconfiguring the architecture of agency

Agents can modify nodes, dependencies, permissions, sites, computational resources, and external access. These are interventions on the **future action space**, not merely actions inside a fixed action space. The new architecture can be better in one dimension and worse in another; the migration path may be infeasible.

Primary work: [adaptive-capability-architecture](https://github.com/muritane/adaptive-capability-architecture), [from_world_constraints_to_endogenous_mobility_frontiers.md](https://github.com/muritane/capability_systems/blob/main/from_world_constraints_to_endogenous_mobility_frontiers.md).

## 6. Distributed systems as analogy, not proof

ROS 1's master-based discovery versus ROS 2's distributed middleware discovery illustrates relocation of architectural responsibilities, **not** the abolition of all intermediaries. A tool-using AI agent may decentralize human workflows while becoming a new coordinator itself. Compare operational dependencies, not slogans like "decentralized = higher capability."

## Scope test

Before adding a new principle, ask:

1. What does it explain that an existing repository does not?
2. What would count as counterevidence?
3. Which variables and mechanisms must be represented?
4. What test or failure case makes the proposed distinction observable?
