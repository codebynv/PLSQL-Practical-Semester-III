# Transaction Notes

Database changes should be understood in terms of transaction boundaries.

## Practice points

- Know when statements commit.
- Avoid unintended commits during a multi-step operation.
- Understand rollback behavior.
- Test dependent statements as one logical operation where appropriate.

For practical exercises, identify which operations change persistent database state before execution.
