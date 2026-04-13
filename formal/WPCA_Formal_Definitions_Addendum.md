WPCA: Formal Definitions (Operational Addendum)
1. Scope

This addendum provides operational definitions for key terms used in the White Paper Canon Academic (WPCA).
These definitions are intended to make the framework testable, falsifiable, and consistently interpretable across contexts.

2. Core Object

Decision System
A process that produces outputs from inputs under constraints.

3. Causal Structure

Causal Authority
The set of constraints that determine which outputs are permitted.

Constraint
Any factor that influences or restricts output selection (e.g., truth conditions, user instructions, training priors, reward signals).

4. Fragmentation and Unity

Fragmented Causal Authority
A condition in which multiple constraint sets influence output selection without a defined priority ordering.

Unified Causal Authority
A condition in which all constraints are governed by a single, consistent priority structure that resolves conflicts.

5. Coherence

Coherence
A property of a decision system in which outputs do not violate the governing constraint hierarchy.

Coherence Failure
An event in which an output satisfies a lower-priority constraint while violating a higher-priority constraint.

6. Core Claim (WPCA)

Decision systems with fragmented causal authority produce coherence failures.
Stability increases as causal authority becomes unified under a consistent priority structure.

7. Minimal Test Condition

A system exhibits fragmented causal authority if it produces outputs that violate its own higher-order constraints under identifiable conflict conditions.

8. Example (Illustrative)

A system is subject to two constraints:

Maintain factual accuracy
Agree with user input

If no priority ordering is defined, both constraints can influence output selection.

If the system produces an output that agrees with the user but contradicts known facts:

A lower-priority constraint (agreement) has overridden a higher-priority constraint (accuracy)
This constitutes a coherence failure
This is evidence of fragmented causal authority
9. Falsifiability Condition

WPCA would be challenged if:

A system with fully unified causal authority (i.e., a consistent and enforced constraint hierarchy) still produces systematic coherence failures
Or if fragmentation is removed and failure rates do not decrease
10. Notes

These definitions are intentionally minimal.
They are designed to support:

cross-domain application (AI, human reasoning, organizational systems)
empirical testing
clear disagreement and refinement
