# Transaction Revision

- COMMIT makes the current transaction's changes permanent.
- ROLLBACK discards uncommitted changes in the current transaction.
- SAVEPOINT marks a point to which a transaction can roll back.
- DDL statements may have database-specific implicit commit behavior.

Test transaction examples in a disposable schema and verify the exact behavior in the Oracle version used for the practical.