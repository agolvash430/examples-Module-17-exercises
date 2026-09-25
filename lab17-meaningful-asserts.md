# Lab 17 — Meaningful Asserts

## Weak
Only checking “no exception thrown” or “result not null” — does not prove the service behaved correctly.

## Strong (Ravi)
Assert the returned status changed from PROSPECT → ACTIVE, assert the repository `save` was called once with the updated customer, and assert no other repository interactions occurred.

## Exception assert (Amina)
Assert that calling activate on an already‑ACTIVE customer throws the illegal‑transition exception, and assert that the repository is *not* called to save or update anything.

## Scope
Pre-lab only.
