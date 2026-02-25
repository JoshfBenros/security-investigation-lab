# Phase 2 – Controlled Anomaly Investigation

---

## Phase Objective

Introduce controlled deviations from established authentication baselines and evaluate their visibility, signal strength, and investigative relevance within Windows Security logs.

This phase focuses on:

- Identifying high-signal vs low-signal anomalies
- Observing failed authentication patterns
- Mapping privilege elevation behavior
- Evaluating timestamp deviations
- Strengthening investigative reasoning

---

# Session 1 – Deviation: Off-Hours Login

## Hypothesis

A login outside the established normal usage window will generate a standard 4624 event but may only differ by timestamp.

Time-based anomalies alone may represent weak signals without additional context.

## Action Performed

(To be completed during session)

## Observed Events

(To be completed during session)

## Analysis

(To evaluate whether timestamp deviation alone is meaningful)

## Conclusion

---

# Session 2 – Deviation: Multiple Failed Login Attempts

## Hypothesis

Repeated failed authentication attempts should generate Event ID 4625 and may indicate brute-force or credential misuse patterns.

## Action Performed

(To be completed during session)

## Observed Events

(To be completed during session)

## Analysis

(To assess pattern strength and correlation)

## Conclusion

---

# Session 3 – Deviation: Privilege Elevation via UAC

## Hypothesis

Triggering administrative elevation from a standard account should produce privilege-related indicators distinct from direct administrator login.

## Action Performed

(To be completed during session)

## Observed Events

(To be completed during session)

## Analysis

(To map elevation event sequence)

## Conclusion

---

# Phase 2 Completion Criteria

Phase 2 is complete when:

- Controlled deviations are documented clearly.
- Signal strength is properly evaluated.
- Privilege elevation behavior is understood.
- Time-based anomalies are contextualized.
- Investigative reasoning is clearly articulated.

Phase 2 in progress.
---

Phase 2 in progress.
