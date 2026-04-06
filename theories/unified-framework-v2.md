# A Unified Framework v2: Ego, Moral Judgment, Narrative Selection, and Automaticity

**Author:** Elad  
**Status:** Draft v0.1  
**Date:** 2026-04-06

## Abstract

This framework unifies four claims. First, the ego is a non-recursive action-driving function rather than a native moral faculty. Second, moral judgment is a special case of recursive evaluation rather than a primitive intuition. Third, in domains with weak correctness pressure, self-explanations are selected primarily for their stabilizing effect on the self-model rather than for their truth. Fourth, automaticity, fluency, certainty, and felt depth do not determine grounding. The result is a single architecture spanning action, moral judgment, self-explanation, and habituation.

## I. Primitive Definitions

Let:

- $D$ — drive-state
- $A$ — action tendency
- $C$ — consequence-space
- $J$ — evaluative judgment
- $V$ — evaluative criterion
- $V_m$ — moral criterion
- $R$ — recursive reasoning-function
- $E$ — ego-function
- $M$ — moral judgment-function
- $I$ — intuition
- $S$ — self-model
- $N$ — candidate self-explanation
- $T$ — underlying causal structure of events
- $K$ — correctness pressure
- $\text{Stab}(N,S)$ — stabilizing effect of narrative $N$ on self-model $S$
- $\tau$ — automaticity
- $\phi$ — grounding

For additional precision:

$$
K = (K_e, K_s, K_t)
$$

where:

- $K_e$ = empirical correction pressure
- $K_s$ = social correction pressure
- $K_t$ = temporal consequence legibility

## II. The Amoral Ego Thesis

### Axiom 1. Primitive action-generation

$$
E : D \to A
$$

### Axiom 2. Non-recursiveness of ego

The ego may be shaped by prior learning, conditioning, and habituation, but it does not itself perform explicit recursive evaluation over action-consequence pairs under a criterion.

### Definition 1. Recursive evaluation

$$
R : A \times C \to J
$$

with:

$$
J = R(A, C \mid V)
$$

### Definition 2. Moral judgment

Not all recursive evaluation is moral. Moral judgment is the special case where recursive evaluation is governed by a specifically moral criterion:

$$
M = R(A, C \mid V_m)
$$

### Proposition 1. Moral emergence

Morality is not a primitive output of $E$. It becomes possible only when recursive reasoning operates over candidate action and projected consequence under $V_m$.

### Corollaries

- Action produced by $E$ alone is pre-moral.
- Motivational conflict is not yet moral judgment.
- Intuition is candidate input, not verdict.

## III. Intuition Without Moral Authority

Let $I$ denote an intuitive response: affectively tagged, often rapid, often automatic, but produced prior to full recursive deliberation.

Then:

$$
I \notin \text{range}(M)
$$

but:

$$
I \in \text{domain}(R)
$$

Intuition may influence judgment, but it is not itself moral judgment. Its authority depends on what survives recursive evaluation under $V_m$, not on how forcefully it appears.

## IV. Automaticity and Grounding

The central non-entailment claim is:

$$
\tau(x) \not\Rightarrow \phi(x)
$$

A response may be rapid, fluent, and deeply habituated without thereby becoming true, justified, or morally authoritative.

If repeated reinforcement produces automaticity:

$$
\text{Training}(x) \to \tau(x)
$$

it still does not follow that:

$$
\tau(x) \Rightarrow \phi(x)
$$

Therefore training does not itself ground.

### Principle

**Automatic is not primitive. Consolidated is not grounded.**

## V. The Self-Stabilizing Narrative Thesis

### Axiom 3. Self-model updating

$$
S(t+1) = f(S(t), N_{\text{selected}})
$$

### Axiom 4. Two selection regimes

When correctness pressure is strong, narrative selection is pushed toward truth-tracking:

$$
K \text{ high} \implies \text{selection}(N) \propto d(N,T)^{-1}
$$

When correctness pressure is weak, narrative selection is pushed toward self-stabilization:

$$
K \text{ low} \implies \text{selection}(N) \propto \text{Stab}(N,S)
$$

### Axiom 5. Consistency-biased updating

Assume the update function $f$ is consistency-biased: once a narrative is integrated, future narrative selection becomes biased toward narratives compatible with the updated self-model.

### Proposition 2. Narrative lock-in

If a stabilizing narrative $N^*$ is selected under low-$K$ conditions and integrated into $S$, then future selection becomes biased toward narratives of similar structure:

$$
S(t+1)=f(S(t),N^*) \implies P(N^*\text{-class}\mid S(t+1)) > P(N^*\text{-class}\mid S(t))
$$

This is narrative lock-in.

### Corollaries

- Coherence and truth can come apart.
- Subjective authenticity is not evidence of causal accuracy.
- Fluency of retrieval may reflect reinforcement depth rather than truth proximity.

## VI. The Unified Principle

### The Ontological–Phenomenological Independence Principle

For any candidate content $x$, the phenomenology of retrieval does not determine grounded status.

For any phenomenological property $\psi$ such as automaticity, felt certainty, affective force, or fluency:

$$
\psi(x) \not\Rightarrow \phi(x)
$$

and:

$$
\psi(x) \not\Rightarrow d(x,T)^{-1} \text{ is high}
$$

and:

$$
\psi(x) \not\Rightarrow x \in \text{range}(M)
$$

So:

- speed does not prove grounding,
- certainty does not prove truth,
- naturalness does not prove morality.

## VII. Structural Failure Modes

| Domain | Primitive Layer | Recursive Layer | Failure Mode |
|---|---|---|---|
| Action | $E:D\to A$ | $R(A,C\mid V)\to J$ | Pre-moral action mistaken for judgment |
| Morality | $I$ as input | $R(A,C\mid V_m)\to M$ | Intuition mistaken for verdict |
| Habituation | Training $\to \tau$ | grounding requires recursive justification | Automaticity mistaken for fundamentality |
| Self-explanation | $\text{Stab}(N,S)$ drives selection under low $K$ | truth-tracking rises with high $K$ | Narrative lock-in |

## VIII. General Corrective Mechanism

Across these domains, the corrective is the same:

**force candidate contents through recursive evaluation under sufficiently high correctness pressure.**

## IX. One-Statement Thesis

The ego generates action without morality. Recursive cognition introduces the possibility of judgment, but judgment becomes moral only when governed by a specifically moral criterion rather than by prudence or strategy alone. In parallel, self-explanations selected under weak correctness pressure drift toward self-stabilization rather than truth. In both domains, the speed, fluency, certainty, or affective intensity of a response provides no authority beyond what is earned by the process that produced it.

## X. Scope

This framework is structural rather than complete. It specifies the architecture within which moral judgment, self-explanation, and habituation must be analyzed. It does not yet specify a final substantive moral criterion. That problem is deferred rather than denied.
