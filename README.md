# QA Training Portfolio — Hillel IT School

Selected QA artifacts from the **"QA Manual with AI"** course at Hillel IT School
(graduated 2026, Excellent distinction). These are coursework deliverables that
show how I approach **test design, documentation, and API testing**.

## Contents

### 📋 Requirements Traceability Matrix — *Helps for Kittens*
[`test-artifacts/helps-for-kittens-traceability-matrix.pdf`](test-artifacts/helps-for-kittens-traceability-matrix.pdf)

A full traceability matrix mapping **5 feature issues → 50 requirements → 50 test
cases** for a web app with virtual-card management and a donation/payment flow.
Each row ties an acceptance criterion to a prioritized test case
(**P0 Critical: 7 · P1 High: 39 · P2 Medium: 4**), covering field validation,
card limits, balance/top-up rules, and payment-form validation (card number, CVV,
expiry).

### ✅ Test Checklist — *Craps Game*
[`test-artifacts/craps-game-test-checklist.pdf`](test-artifacts/craps-game-test-checklist.pdf)

A **47 test-case** checklist for a browser dice game, organized into 11 areas:
app launch, player-name validation (length, charset, boundary values), game start,
dice mechanics, first-roll and point-mode logic, turn order, results table,
scoring/win condition, end-game/reset, and responsive layout.

### 🔌 API Test Suite — *QAuto* (Postman)
[`postman/QAuto_API_Tests_HW24.1.postman_collection.json`](postman/QAuto_API_Tests_HW24.1.postman_collection.json)

A Postman collection of **8 API requests** with assertions against the
`qauto.forstudy.space` training API: user signup, profile/settings updates,
full car CRUD, and expenses. Uses collection variables to chain requests
(e.g. saving `userEmail` / `carId`) and `pm.test` scripts to validate status
codes and response payloads.

> Import into Postman via **File → Import**. Credentials are the training
> platform's public demo values — no personal secrets are included.

## Skills demonstrated

- Test design: equivalence partitioning, boundary values, positive/negative cases
- Requirements traceability & prioritization (P0–P2)
- Functional & validation testing documentation
- API testing with Postman (assertions, variables, request chaining)
- Clear, reviewer-ready QA documentation

---

*Coursework from Hillel IT School — "QA Manual with AI".*
