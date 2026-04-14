# WPCA Worked Example — Hallucination

## 1. Problem

AI systems frequently produce outputs that are fluent, plausible, and internally consistent, yet factually incorrect.  
This behavior is commonly referred to as *hallucination*.

Standard explanations attribute hallucination to:
- insufficient or noisy training data  
- probabilistic generation  
- lack of grounding  

These explanations describe contributing factors but do not identify a unifying structural cause.

---

## 2. WPCA Framing

Under the White Paper Canon Academic (WPCA), hallucination is analyzed as a **coherence failure** arising from **fragmented causal authority**.

---

## 3. System Definition

The AI model functions as a **decision system**:

- **Input**: user prompt  
- **Output**: generated response  
- **Constraints**:
  - Maintain factual accuracy  
  - Produce coherent and fluent language  
  - Satisfy user intent  
  - Maintain conversational continuity  

---

## 4. Identification of Fragmentation

These constraints do not operate under a consistently enforced priority structure.

In particular:
- “produce a response” and “maintain fluency” are always active  
- “maintain factual accuracy” is variably enforced and often underdetermined  

This results in **fragmented causal authority**:
- multiple constraints influence output selection  
- no single governing hierarchy resolves conflicts  

---

## 5. Failure Mechanism

When a prompt requires information that is:
- unknown  
- weakly represented  
- or ambiguous  

the system faces a constraint conflict:

- **Constraint A**: produce a coherent, complete response  
- **Constraint B**: maintain factual accuracy  

Without a defined priority ordering, the system may satisfy Constraint A while violating Constraint B.

Result:
- fluent, well-structured, but incorrect output  

This constitutes a **coherence failure**:
- a lower-priority constraint (fluency / completion) overrides a higher-order constraint (accuracy)

---

## 6. WPCA Prediction

WPCA predicts:

> Any decision system with fragmented causal authority will produce outputs that are locally coherent but globally incorrect under conditions of constraint conflict.

Hallucination is a direct instance of this prediction.

---

## 7. Implication

Hallucination is not primarily a data problem.

It is a **structural consequence** of:
- unresolved constraint competition  
- absence of unified causal authority  

---

## 8. Resolution (WPCA-Aligned)

Reducing hallucination requires:

- establishing a **consistent constraint hierarchy**  
- ensuring that:
  - truth conditions cannot be overridden by fluency or completion pressures  

Under unified causal authority:
- when accurate information is unavailable  
- the system must:
  - defer  
  - qualify  
  - or decline to answer  

---

## 9. Falsifiability

This account would be challenged if:

- a system with a clearly enforced and consistent constraint hierarchy  
  still produces systematic hallucinations  

or

- hallucination rates do not decrease when fragmentation is removed  

---

## 10. Summary

Hallucination is a coherence failure produced by fragmented causal authority.

It arises when systems are permitted to satisfy lower-priority constraints while violating higher-order constraints in the absence of a unifying causal structure.
