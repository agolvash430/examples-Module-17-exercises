# Lab 17 — AAA Service Tests Plan

## Happy path (Arrange / Act / Assert)
Arrange: valid customer fixture (CUS‑1001 ACTIVE), valid request, and a service wired with a fake repository.  
Act: call the service method (e.g., activate, update email).  
Assert: returned DTO matches expectations, repository was called once, and no exceptions thrown.

## Not found
Arrange: repository returns empty for CUS‑9999.  
Act: call the service method.  
Assert: service throws NotFoundException and no state‑changing repository calls occur.

## Illegal
Arrange: customer in a state where the requested transition is forbidden (e.g., Amina already ACTIVE).  
Act: call the service method.  
Assert: service throws IllegalStateException / conflict error and repository is not invoked for updates.

## Scope
Pre-lab only.
