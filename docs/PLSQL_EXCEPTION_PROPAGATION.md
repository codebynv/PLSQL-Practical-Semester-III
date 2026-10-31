# PL/SQL Exception Propagation

When an exception is raised:

- The current block searches for a matching handler.
- If no handler matches, the exception propagates to an enclosing block or caller.
- A handler should not silently hide an unexpected failure.
- Transaction effects should be checked explicitly.
- Use RAISE when an exception must be propagated after local handling.

Test nested blocks with both handled and unhandled exceptions in a disposable schema.