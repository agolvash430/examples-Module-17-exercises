# Lab 17 — Fill JaCoCo Gate Narrative TODOs

Tool: JaCoCo (line coverage gate in Maven)

Maven phase idea: `verify` phase so coverage is checked before packaging

Target line coverage % (lab goal): 80%

Package to measure: `com.example.customer` (service + validator package only)

Gap you still expect: Repository layer not covered (mocked), controller layer not part of this pre‑lab

Mockito depth in this pre-lab? Shallow — only basic stubbing and verifying interactions

## AAA line
Arrange the fixture, Act on the service, Assert both the result and the repository interactions to drive real line coverage.

## Scope
