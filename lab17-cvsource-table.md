# Lab 17 — CsvSource Table Design

| inputStatus | valid? |
| --- | --- |
| ACTIVE | true |
| PROSPECT | true |
| ACTVE | false |
| (blank) | false |
| (your extra invalid) | false |

## Runtime note
CsvSource passes raw strings exactly as written — typos, blanks, and malformed values must be treated as invalid and asserted accordingly.

## Scope
Pre-lab only.
