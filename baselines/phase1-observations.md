# Phase 1 – Baseline Observations

---

## Session 1 – 2/18/26

## Purpose:

Establish baseline authentication behavior.

## Standard User Login

Observed Events:
- Event ID: 4624
- Log Name: Security
- Logon Type: 2 (Interactive)
- Authentication Package: Negotiate
- Notes:
  - Normal local login observed
  - No 4672 event present (no elevated privileges)

## Administrator Login

Observed Differences:
- Additional fields:
  - Admin account login generated expected privileged session.
- Privilege markers:
  - No detailed analysis yet (admin baseline to be observed in Session 2).
- Session length:
  - Very short; used only to review logs.

## Initial Takeaways

- What surprised me:
- What was repetitive:
- What seemed high-signal:

---

## Session 2 – 2/19/26
