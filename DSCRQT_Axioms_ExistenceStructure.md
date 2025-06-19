# DSCRQT – Axioms on Ontological Structure of Existence

## Purpose
This document contains an axiom-based framework to describe the logic of existence that underlies the theory DSCRQT (Dual State Complex Realisation Quantum Theory). It formalizes the distinction between **concrete states** and their **ontological realisation status**.

---

## Axiomatic Structure

### 🔹 A1 – Meta-States
There exist exactly two ontological meta-states:

\[ \text{META} = \{\text{Exists}, \text{Does-Not-Exist}\} \]

These are disjoint and exhaustive. They do not describe the content of a state, but its assignment in terms of reality.

---

### 🔹 A2 – Definition of a State
A state is a concrete, distinguishable, and potentially measurable entity of description:

\[ \text{STATE} = \{S_1, S_2, \ldots, S_n\} \]

Such states may include:
- classical quantities (e.g., position, momentum)
- quantum eigenstates (e.g., spin-up, spin-down)
- qualitative conditions (e.g., being ice, being water)

The concept of a state remains flexible, as long as Axiom A3 remains applicable.

---

### 🔹 A3 – Ontological Assignment
Every state belongs **either** to the meta-state "Exists" **or** to "Does-Not-Exist".

\[
\forall S \in \text{STATE}:\quad (S \in \text{Exists}) \lor (S \in \text{Does-Not-Exist}) \quad \land \quad \neg((S \in \text{Exists}) \land (S \in \text{Does-Not-Exist}))
\]

This is the formal representation of the Aristotelian law of the excluded middle, applied to state ontology.

---

### 🔹 A4 – Realisation and Non-Realisation
To distinguish the semantics of existence more precisely, we introduce the distinction between realisation and non-realisation based on interaction with the environment:

- **Realised:**  
  A state is realised if it belongs to the meta-state "Exists" **and interacts with the environment**. It produces causal effect, observable change, or measurable outcome. It is thus active within the universe.

- **Not Realised (potential):**  
  A state is not realised if it belongs to the meta-state "Does-Not-Exist" or—despite existing—**does not interact with the environment**. It is effectively hidden from the universe and has no causal footprint.

Formalisation:

\[
\text{Realised}(S) \Leftrightarrow S \in \text{Exists} \land \text{Interacts}(S)
\]
\[
\text{Not-Realised}(S) \Leftrightarrow S \in \text{Does-Not-Exist} \lor \neg\text{Interacts}(S)
\]

---

## Future Expansion
This axiom set is the **first version** of an ontological framework for DSCRQT. Further axioms may be added to cover dynamics, temporality, observation and mathematical formalism. Future directions include:

- A5: Temporal dependency (existence over time)
- A6: Observation and measurement as criteria for realisation
- A7: Coupling to state vectors in complex vector space (e.g., via projections, norm, phase)