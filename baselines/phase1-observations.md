# Phase 1 – Baseline Observations

---

## Session 1 – 2/18/26

### Purpose:

Establish baseline authentication behavior.

### Standard User Login

Observed Events:
- Event ID: 4624
- Log Name: Security
- Logon Type: 2 (Interactive)
- Authentication Package: Negotiate
- Notes:
  - Normal local login observed
  - No 4672 event present (no elevated privileges)

### Administrator Login

Observed Differences:
- Additional fields:
  - Admin account login generated expected privileged session.
- Privilege markers:
  - No detailed analysis yet (admin baseline to be observed in Session 2).
- Session length:
  - Very short; used only to review logs.

### Initial Takeaways

- What surprised me:
- What was repetitive:
- What seemed high-signal:

---

## Session 2 – 2/19/26

### Purpose:
Confirm administrator privilege baseline and identify privilege assignment indicators.

### Administrator Login

Observed Events:
- Event ID: 4624
- Event ID: 4672 (Special privileges assigned)
- Logon Type: 2 (Interactive)
- Authentication Package: Negotiate

Observed Differences: 
- 4672 event present for admin login.
- 4672 confirms elevated privilege assignment at session start.
- Not observed in standard user baseline.

Session Length:
- Short, used only for log review.

#### Evidence

![Admin Privilege Assignment](../evidence/phase1/phase1-session2-admin-4672.png)

---

