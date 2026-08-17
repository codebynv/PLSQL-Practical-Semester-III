🐘 PL/SQL Practical Lab — Semester III

A complete collection of PL/SQL practical programs covering PL/SQL fundamentals, control flow, cursors, parameterised cursors, debugging, and database programming.

<div align="center">
🎓 B.Sc. Information Technology — Semester III

Student: Nirav Vala
Roll No.: 33
University: LJ University

<br>








</div>
📌 About This Repository

This repository contains my PL/SQL Practical Laboratory work for Semester III.

The programs are organized according to the practical exercises provided for the course and are written to be executed using Oracle SQL*Plus.

The repository focuses on writing complete anonymous PL/SQL blocks, understanding procedural SQL concepts, working with database tables, and implementing cursor-based database operations.

🗂️ Repository Structure
PLSQL-Practical/
│
├── 📁 Unit 1/
│   ├── P1.1_...
│   ├── P1.2_...
│   ├── P1.3_...
│   └── ...
│
├── 📁 Unit 2/
│   ├── P2.1_...
│   ├── P2.2_...
│   ├── P2.3_...
│   └── ...
│
├── 📁 Unit 3/
│   │
│   ├── 📁 Section 1 - Schema Setup/
│   │
│   ├── 📁 Section 2 - Simple Cursors/
│   │
│   ├── 📁 Section 3 - Parameterised Cursors/
│   │
│   └── 📁 Section 4 - Trace Debug Short Answer/
│
└── 📄 README.md
📚 Practical Coverage
🟦 Unit 1 — PL/SQL Fundamentals

Covers the fundamentals of PL/SQL programming and anonymous blocks.

Topics
PL/SQL block structure
Variables and constants
%TYPE
%ROWTYPE
SELECT INTO
Conditional statements
IF / ELSIF / ELSE
CASE
Loops
FOR, WHILE
Nested blocks
Exception handling
User-defined exceptions
SQL functions inside PL/SQL
Date and numeric operations

Status: 23 / 23 ✅

🟩 Unit 2 — PL/SQL Programming Applications

Unit 2 focuses on applying PL/SQL concepts to practical problem-solving.

Programs include
🎓 Grade Card System
💰 Income Tax Calculator
🏧 ATM Machine Simulation
🔢 Loops & Patterns
🧮 Fibonacci, Prime & GCD programs
🍔 Zomato Delivery Price Engine
📊 Student Result & Attendance System
🏦 Loan EMI Affordability Checker

Status: 8 / 8 ✅

🟨 Unit 3 — PL/SQL Cursors

Unit 3 focuses heavily on Simple Cursors, Parameterised Cursors and Cursor debugging.

The official practical is divided into four sections.

01 — Library Schema Setup

A complete Library Management database is used throughout the cursor exercises.

PUBLISHER
    │
    ▼
  BOOK
    │
    ▼
BOOK_ISSUE ◄──── LIB_MEMBER

The schema contains:

PUBLISHER
BOOK
LIB_MEMBER
BOOK_ISSUE

The provided dataset contains 5 publishers, 12 books, 8 members and 12 issues.

02 — Simple / Explicit Cursors

12 practicals

Concepts covered:

DECLARE
   ↓
OPEN
   ↓
FETCH
   ↓
%NOTFOUND
   ↓
CLOSE

Also includes:

Cursor FOR LOOP
%ROWTYPE
%ROWCOUNT
%ISOPEN
Cursor joins
SELECT ... FOR UPDATE
WHERE CURRENT OF
Stock and price updates
03 — Parameterised Cursors

12 practicals

Concepts covered:

Cursor parameters
Substitution variables
Case-insensitive parameters
Multiple cursor parameters
Default cursor parameters
Nested cursors
Boolean flags
Date-based cursor filtering
Parameterised FOR UPDATE
WHERE CURRENT OF
Overdue fine calculation

The official exercise requires parameterised cursors to accept values at open time and specifically notes that cursor parameters should not have a datatype size such as VARCHAR2(20).

04 — Trace, Debug & Short Answer

6 questions

Focuses on understanding cursor behaviour rather than simply writing programs.

Topics include:

ORA-01001
Invalid cursor behaviour
Cursor parameter compilation errors
%ROWCOUNT
Missing cursor arguments
Default cursor parameters
Implicit vs explicit vs parameterised cursors
%FOUND
%NOTFOUND
%ROWCOUNT
%ISOPEN

The official instructions specify that these questions should primarily be answered in the journal, with code execution used to confirm predictions.

🧠 Concepts Practiced
PL/SQL
│
├── Anonymous Blocks
│
├── Variables & Constants
│
├── %TYPE
│
├── %ROWTYPE
│
├── SELECT INTO
│
├── Conditions
│   ├── IF / ELSIF / ELSE
│   └── CASE
│
├── Loops
│   ├── FOR
│   ├── WHILE
│   └── Nested Loops
│
├── Exception Handling
│
└── Cursors
    │
    ├── Simple / Explicit
    │   ├── OPEN
    │   ├── FETCH
    │   ├── CLOSE
    │   ├── %FOUND
    │   ├── %NOTFOUND
    │   ├── %ROWCOUNT
    │   └── %ISOPEN
    │
    └── Parameterised
        ├── Cursor Parameters
        ├── DEFAULT Parameters
        ├── Nested Cursors
        ├── FOR UPDATE
        └── WHERE CURRENT OF
⚙️ Environment
Database
Oracle Database
Execution Environment
Oracle SQL*Plus
Output
SET SERVEROUTPUT ON;

Every practical is designed as a complete anonymous PL/SQL block and is terminated using:

/

as required by the practical instructions.

▶️ How to Run
1. Open SQL*Plus
sqlplus username/password
2. Enable output
SET SERVEROUTPUT ON;
3. Run a practical
@filename.sql

or:

START filename.sql
4. For substitution-variable programs

For example:

&category

SQL*Plus will ask for the value.

Enter the required value and execute the program.

📸 Output Documentation

Each practical contains its corresponding SQL code and can be accompanied by its SQL*Plus output screenshot.

Recommended naming:

Question_Output.png

Example:

3.3.12_Parameterised_Cursor_Name_Initial_Output.png
📊 Completion Tracker
╔══════════════════════════════════════╗
║       PL/SQL PRACTICAL PROGRESS      ║
╠══════════════════════════════════════╣
║                                      ║
║  Unit 1  ████████████████████ 100%  ║
║  Unit 2  ████████████████████ 100%  ║
║  Unit 3  ████████████████████ 100%  ║
║                                      ║
╠══════════════════════════════════════╣
║             STATUS: COMPLETE ✅      ║
╚══════════════════════════════════════╝
🧪 Key SQL*Plus Notes
Enable output
SET SERVEROUTPUT ON;
Run a script
@filename.sql
End a PL/SQL block
END;
/
Substitution variable
'&category'
Cursor parameter
CURSOR c_book(p_category VARCHAR2) IS

Do not specify a size for a parameterised cursor parameter:

-- ❌ Wrong
p_category VARCHAR2(20)


-- ✅ Correct
p_category VARCHAR2
📁 Repository Philosophy

This repository is organized to keep the practical work:

Easy to navigate
Easy to execute
Easy to review
Easy to revise before exams
Aligned with the university practical exercises

The goal is not just to store code, but to maintain a clean record of the Semester III PL/SQL practical journey.

👨‍💻 Student
<div align="center">
Nirav Vala

B.Sc. Information Technology — Semester III
Roll No.: 33

<br>

Learning → Building → Debugging → Improving

</div>
<div align="center">
⭐ PL/SQL Practical — Semester III

23 Unit 1 Programs • 8 Unit 2 Programs • Cursor Exercises

</div>