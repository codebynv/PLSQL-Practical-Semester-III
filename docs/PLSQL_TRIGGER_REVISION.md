# PL/SQL Trigger Revision

A trigger runs automatically in response to a defined database event.

Review:
- the triggering event and timing,
- row-level versus statement-level behavior,
- OLD and NEW values where applicable,
- mutating-table restrictions,
- side effects and transaction behavior,
- recursion and unexpected repeated execution.

Test triggers with controlled INSERT, UPDATE, and DELETE statements in a disposable schema. Verify resulting rows and exceptions.