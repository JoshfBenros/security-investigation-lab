# Security Investigation Lab (Behavioral Baselining Project)

## Purpose

This project is a controlled host-based security investigation lab designed to build practical investigative skills. 

The focus is not on attack simulation, but on:
- Establishing behavioral baselines
- Identifying deviations
- Analyzing authentication and privilege patterns
- Practicing structured investigation and documentation

The goal is to develop the reasoning process used by Security Analysts and SOC teams before scaling to enterprise or cloud environments.

---

## Scope (2–4 Weeks)

This project runs in a controlled local Windows environment with:

- 1 standard user account (represents a normal employee)
- 1 administrator account (represents IT / privileged access)

No external attack tools are used. All deviations are intentionally introduced and documented.

The emphasis is on:
- Observation
- Pattern recognition
- Timeline reconstruction
- Evidence-based conclusions

---

## Identity Model

### 1. Standard User (lab_user)
Represents a normal employee.

Expected behavior:
- Regular login during consistent hours
- Web browsing
- Opening files
- Low-risk activity
- No privilege escalation

---

### 2. Administrator (lab_admin)
Represents IT / privileged access.

Expected behavior:
- Rare login
- Short sessions
- Purpose-driven actions
- High-impact changes only when necessary
- Break-glass mindset

---

## Investigation Mindset

This project treats security as digital investigation under uncertainty.

Key principles:

- Suspicion is based on deviation from baseline
- Behavior is analyzed before intent is assumed
- One variable is changed at a time
- Conclusions are evidence-based and documented
- “Inconclusive” is an acceptable outcome

---

## Project Phases

Week 1 – Establish baseline behavior  
Week 2 – Introduce controlled deviations  
Week 3 – Improve investigative reasoning  
Week 4 – Reflection and scaling considerations  

---

## Long-Term Objective

Develop investigative discipline that scales to:

- SOC environments
- Enterprise log analysis
- Cloud IAM & audit log investigation
- Security engineering design decisions
