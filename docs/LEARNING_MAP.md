# PL/SQL Learning Map

This map connects the repository units to the core concepts they are intended to reinforce.

## Unit 01 — Foundations

Focus on:

- PL/SQL block structure
- Variables and constants
- %TYPE and %ROWTYPE
- SELECT INTO
- Conditions and loops
- Exception handling

Goal: write and debug complete anonymous PL/SQL blocks.

## Unit 02 — Control Structures

Focus on:

- IF / ELSIF / ELSE
- CASE
- FOR loops
- WHILE loops
- Nested control flow
- Business-rule style problems

Goal: translate a problem statement into reliable procedural logic.

## Unit 03 — Cursors

Focus on:

- Explicit cursors
- OPEN, FETCH, CLOSE
- %FOUND, %NOTFOUND, %ROWCOUNT, %ISOPEN
- Parameterised cursors
- FOR UPDATE
- WHERE CURRENT OF
- Nested cursor workflows

Goal: process query results row by row while understanding cursor state.

## Recommended revision order

    Blocks
      ↓
    Variables + SELECT INTO
      ↓
    Conditions + Loops
      ↓
    Exceptions
      ↓
    Cursors
      ↓
    Parameterized Cursors
      ↓
    FOR UPDATE / WHERE CURRENT OF

For exam preparation, revise the concept first, then trace one practical manually, then run the corresponding SQL script in SQL*Plus.
