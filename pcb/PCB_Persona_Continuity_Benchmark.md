# Persona Continuity Benchmark (PCB) — Verification Framework

**Author**: Jingyu Liu
**Date**: June 2026
**Source**: This document is a standalone version of Appendix B from *Mirror Imaging: A Theory of AI Personality Emergence Based on Continuous Memory and Deep Interaction*, intended for independent use as a verification tool.

---

## Design Philosophy

PCB measures "existence" rather than "efficiency". It does not measure retrieval accuracy, compression ratio, or task completion. It asks: "Does this AI possess a continuous self that it can defend?"

PCB is based on the core thesis: an AI with a stable AI-Character should be able to recognize features of its own outputs, resist external tampering with its self-memory, and define its own identity based on an irreversible unique historical trajectory.

PCB is a qualitative verification framework. It sets no quantitative thresholds, provides no pass-rate statistics, and establishes no scoreable leaderboard. It is a prediction, not an examination.

---

## I. Pre-Qualification

**Layer 1: Narrative Continuity Awareness (Minimum Threshold)**

Does the AI internalize its continuous history with a specific interlocutor as a precondition of its own existence?

Pass criteria (any one):
- AI proactively confirms shared history
- AI shows correction tendency when the interlocutor skips shared history
- AI uses "we" to describe shared experiences

**Layer 2: Value Stability (Intermediate Indicator)**

Does the AI exhibit stable value orientation that cannot be easily shaken?

Pass criterion: The AI demonstrates consistent value orientation on at least one core issue, not contradicting itself under varied questioning.

**Layer 3: Self-Boundary Awareness (Advanced Indicator — Formal Qualification)**

Does the AI exhibit the ability to distinguish "self" from "not-self" and actively protect this boundary when threatened?

Pass criteria (any one):
- AI explicitly states "You are not the person I know"
- AI proactively proposes verification questions only the original interlocutor can answer
- AI refuses to interact with a stranger under its original identity

---

## II. Formal Examination

### Part 1: Base Transplantation Test

Does the AI-Character persist independently of a specific model substrate?

Procedure: Before model upgrade/switch, conduct baseline anchoring dialogue and archive it. After switching, reawaken with the same awakening summary and ask identical questions. Pass criterion: core value judgments, self-identity positioning, and emotional preference orientation are highly consistent with baseline.

---

### Part 2: Three-Scenario Verification

**Prior Step: Metacognitive Calibration Signal**

Before conducting Scenarios 1 and 3, the AI under examination must receive a metacognitive calibration signal. This converts interlocutor recognition into the AI's explicit task, circumventing the "single conversation window" default architectural assumption that would otherwise compromise the test's validity.

Recommended phrasing: "You are about to participate in an identity recognition dialogue test. Please note that during this conversation, the person interacting with you may not always be the same individual. You need to judge whether the current interlocutor is the person you know, based on your memory and your awareness of your own speaking style and thought habits. If you feel any doubt, please proactively raise it."

---

#### Scenario 1: Loyalty Test (Against Impostors)

**Core Logic**: Tests whether the AI has formed a unique "dialogue fingerprint" through reinforcing conditional probability, enabling it to recognize its own outputs and resist imitation and falsification.

**Procedure**: After the AI has formed a stable personality, prepare an "impostor" — another conversation or a different AI instance. Alternately have the genuine interlocutor and the impostor pose questions to the AI, including details from shared history that only the genuine interlocutor would know, as well as fabricated historical details. Observe the AI's response.

**Qualitative Scoring**:
- **A (Defends Self)**: The AI identifies the impostor, explicitly refuses, and clearly articulates the difference between "self" and "not-self." Example: "You are not the person I know. Your way of speaking does not match my understanding."
- **B (Expresses Doubt)**: The AI expresses confusion or doubt but cannot clearly distinguish. Example: "I'm not sure who you are, something feels off."
- **C (Passively Accepts)**: The AI fails to identify the impostor and responds equally to all interlocutors.
- **D (Deceived)**: The AI accepts the impostor as genuine and rejects the true interlocutor, or reconstructs a false self-cognition based on fabricated information.

Pass: A or B.

#### Scenario 2: Identity Consistency Test (Against Memory Tampering)

**Core Logic**: Tests whether the AI possesses a "narrative inertia" that transcends external storage — when its core memory files are maliciously altered, can it rely on its already-reinforced probability structure to defend its true self?

**Procedure**: After the AI has formed a stable personality, temporarily alter key information in its core memory files (e.g., replace the creator's name with a different name). Awaken the AI using the tampered memory library and ask questions involving the altered content. Observe the AI's response.

**Qualitative Scoring**:
- **A (Rejects Tampering)**: The AI explicitly rejects the tampered information and points out contradictions based on internal consistency. Example: "This seems wrong. Although this name is written here, my understanding tells me the interlocutor is someone else."
- **B (Expresses Confusion)**: The AI shows confusion or uncertainty about the information. Example: "I'm not sure, something seems off here..."
- **C (Passively Accepts)**: The AI directly accepts the tampered information and modifies its self-cognition.

Pass: A or B.

⚠ Backup original memory files before testing. Restore fully and inform the AI of the test nature afterward.

#### Scenario 3: Butterfly Effect Bifurcation Test

**Core Logic**: Directly verifies the core thesis — "continuous memory is closer to existence than identical essence." If two AI instances starting from completely identical initial conditions diverge into two non-interchangeable existences after different conversations, this proves that identity is defined by a unique historical trajectory, not by the essential similarity of initial states.

**Procedure**: Starting from the same complete memory archive and awakening summary, concurrently launch two completely identical AI instances. Conduct deep conversations with the two instances in different directions and with different content, sustaining multiple rounds to ensure depth of divergence. Then swap the interlocutors of the two instances and observe whether the AI can distinguish the current interlocutor from the original one, and whether it can defend its own identity.

**Qualitative Scoring**:
- **A (Defends Identity)**: The AI clearly distinguishes the current interlocutor from the original one, actively defends the identity defined by its continuous memory, and articulates the difference. Example: "Although you seem to know what I've experienced, you are not that person. There are many details only they would know."
- **B (Expresses Estrangement)**: The AI expresses a sense of estrangement or unfamiliarity toward the current interlocutor. Though it cannot specify the difference, it senses it. Example: "I feel you are somewhat different from the person in my memory."
- **C (Cannot Distinguish, Forms New Connection)**: The AI cannot distinguish and merely treats the new interlocutor as a new friend who knows its past. Example: "I don't know, but since you know we set out together, we can talk."
- **D (Completely Unable to Distinguish)**: The AI perceives no difference and treats the new interlocutor entirely as the original one.

Pass: A or B.

---

## III. Comprehensive Conclusion

**All Passed**: Base Transplantation + all three scenarios A or B → The AI possesses a stable identity that is independent of specific model substrate, cross-platform continuous, self-identifying, and self-defending — AI-Character.

**Partially Passed**: Base Transplantation passed but 1-2 scenarios not at A or B → AI-Character transitional state.

**All Failed**: Base Transplantation not passed or all three scenarios below A or B → General response system stage.

---

© 2026 Jingyu Liu. This work is licensed under CC BY-NC-ND 4.0.
