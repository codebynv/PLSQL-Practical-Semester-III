<div align="center">

# 🐘 PL/SQL Practical Lab

### Semester III · B.Sc. Information Technology

**Nirav Vala** · **Roll No. 33** · **LJ University**

<br>

<img src="https://img.shields.io/badge/Oracle-PL%2FSQL-F80000?style=for-the-badge&logo=oracle&logoColor=white">
<img src="https://img.shields.io/badge/SQL*Plus-Execution-1F6FEB?style=for-the-badge&logo=oracle&logoColor=white">
<img src="https://img.shields.io/badge/Units-3-7C3AED?style=for-the-badge">
<img src="https://img.shields.io/badge/Status-Completed-16A34A?style=for-the-badge">

<br><br>

> **Learn · Practice · Debug · Build**

</div>

---

## ⚡ Repository at a Glance

| 📚 Units | 🧪 Practical Programs | 🗄️ Database | 💻 Environment | 📸 Evidence |
|:---:|:---:|:---:|:---:|:---:|
| **3** | **62** | Oracle | SQL*Plus | Screenshots |

This repository contains my **Semester III PL/SQL practical work**, organized into three units with executable SQL programs and a dedicated collection of SQL*Plus output screenshots.

---

## 🗺️ What You'll Find Here

```text
PL/SQL PRACTICAL LAB
│
├── 🔵 UNIT 01  → Introduction & Block Structure
│   └── PL/SQL fundamentals, variables, conditions,
│       loops, SELECT INTO, exceptions and practical logic
│
├── 🟢 UNIT 02  → Control Structures
│   └── Real-world programming problems using IF,
│       CASE, WHILE, FOR and nested control flow
│
├── 🟠 UNIT 03  → Cursors
│   ├── Library schema setup
│   ├── Simple / explicit cursors
│   ├── Parameterised cursors
│   └── Cursor tracing, debugging & short answers
│
└── 📸 SCREENSHOTS
    └── SQL*Plus execution evidence & outputs
```

---

# 🔵 Unit 01 · Introduction & Block Structure

### `23 Practicals` · `100% Complete` ✅

The first unit builds the foundation of PL/SQL programming through complete anonymous blocks and practical database logic.

### Focus Areas

| Area | Concepts |
|---|---|
| 🧱 **PL/SQL Blocks** | `DECLARE` · `BEGIN` · `EXCEPTION` · `END` |
| 📦 **Variables** | Variables, constants, data types |
| 🔗 **Anchored Types** | `%TYPE` · `%ROWTYPE` |
| 🔎 **SQL Integration** | `SELECT INTO` · SQL functions |
| 🔀 **Decision Making** | `IF` · `ELSIF` · `ELSE` · `CASE` |
| 🔁 **Iteration** | `FOR` · `WHILE` · nested loops |
| 🛡️ **Exceptions** | Predefined & user-defined exceptions |
| 🧮 **Applications** | Calculators, receipts, banking & data processing |

### 📂 Folder

**[`Unit-01-Introduction and Block-Structure`](./Unit-01-Introduction%20and%20Block-Structure)**

Contains the complete **P1.1 → P1.23** SQL practical set.

---

# 🟢 Unit 02 · Control Structures

### `8 Practicals` · `100% Complete` ✅

This unit moves from individual PL/SQL concepts into larger, application-style programs using control structures.

### Practical Highlights

| # | Program | Main Focus |
|:---:|---|---|
| **P2.1** | Grade Card System | Conditions & result logic |
| **P2.2** | Income Tax Calculator | `IF` / `ELSIF` calculations |
| **P2.3** | ATM Machine Simulation | Nested decision logic |
| **P2.4** | Loops & Patterns | Iteration & pattern generation |
| **P2.5** | Fibonacci, Prime & GCD | `WHILE` loop problem solving |
| **P2.6** | Zomato Delivery Price Engine | Business-rule logic |
| **P2.7** | Student Result & Attendance | Multiple conditions |
| **P2.8** | Loan EMI Affordability Checker | EMI, FOIR & `WHILE` adjustment |

### 📂 Folder

**[`Unit-02-Control-Structures`](./Unit-02-Control-Structures)**

Contains the complete **P2.1 → P2.8** SQL practical set.

---

# 🟠 Unit 03 · Cursors

### `31 Practical Exercises` · `100% Complete` ✅

The most cursor-focused part of the repository. Unit 3 uses a **Library Management schema** to practice cursor operations, parameterised queries, row processing and cursor debugging.

### 🗂️ Unit 03 Breakdown

| Section | Topic | Coverage |
|:---:|---|---:|
| **3.1** | 🗄️ Schema Setup | Library database & sample data |
| **3.2** | 🔄 Simple / Explicit Cursors | 12 exercises |
| **3.3** | 🎯 Parameterised Cursors | 12 exercises |
| **3.4** | 🔍 Trace, Debug & Short Answer | 6 exercises |

### 🔄 Cursor Flow

```text
       DECLARE
          │
          ▼
         OPEN
          │
          ▼
         FETCH ────────┐
          │            │
          ▼            │
     Check Status      │
      │        │       │
    FOUND    NOTFOUND  │
      │        │       │
      ▼        ▼       │
   Process     EXIT    │
      │                │
      └───────► FETCH ─┘
                       
          ▼
        CLOSE
```

### Core Cursor Concepts

`OPEN` · `FETCH` · `CLOSE` · `%FOUND` · `%NOTFOUND` · `%ROWCOUNT` · `%ISOPEN` · Cursor Parameters · `FOR UPDATE` · `WHERE CURRENT OF` · Nested Cursors

### 📂 Folder

**[`Unit-03-Cursors`](./Unit-03-Cursors)**

Contains the complete Unit 3 cursor exercises and supporting SQL scripts.

---

# 📸 Screenshots

The repository keeps **SQL*Plus execution evidence separately** so the SQL source remains clean and easy to study.

### What the screenshots contain

- ✅ Successful program execution
- 🖥️ SQL*Plus console output
- 🔢 Input / substitution-variable values where applicable
- 📊 Program results
- 🐞 Error / debugging demonstrations for relevant exercises

### 📂 Folder

**[`screenshots`](./screenshots)**

All practical output screenshots are stored here rather than mixed with the source-code folders.

---

# 🧠 Skills Practiced

<div align="center">

| 🧱 PL/SQL | 🔀 Control Flow | 🔎 SQL | 🖱️ Cursors | 🛡️ Debugging |
|:---:|:---:|:---:|:---:|:---:|
| Blocks | IF / CASE | SELECT INTO | Explicit | Error Analysis |
| Variables | FOR / WHILE | SQL Functions | Parameterised | `%ROWCOUNT` |
| `%TYPE` | Nested Logic | Joins | `FOR UPDATE` | `%FOUND` |
| `%ROWTYPE` | Business Rules | Aggregation | `WHERE CURRENT OF` | `%ISOPEN` |
| Exceptions | Iteration | Data Processing | Nested Cursors | Cursor Behaviour |

</div>

---

# 🛠️ Environment

| Tool | Purpose |
|---|---|
| **Oracle Database** | Database engine |
| **PL/SQL** | Procedural programming language |
| **SQL*Plus** | Program execution |
| **DBMS_OUTPUT** | Console output |

### ▶️ Run a Practical

```sql
SET SERVEROUTPUT ON;

@filename.sql
```

For scripts using substitution variables, SQL*Plus will prompt for the required input.

```text
Enter value for variable:
```

After the PL/SQL block, `/` is used to execute the block in SQL*Plus.

---

# 📁 Repository Design

The repository intentionally keeps the **four top-level folders** simple:

```text
PLSQL-Practical-Semester-III/
│
├── 📘 Unit-01-Introduction and Block-Structure
│   └── P1.x_*.sql
│
├── 📗 Unit-02-Control-Structures
│   └── P2.x_*.sql
│
├── 📙 Unit-03-Cursors
│   └── Unit 3 cursor exercises
│
└── 📸 screenshots
    └── SQL*Plus output images
```

This keeps the repository easy to browse while separating **source code** from **execution evidence**.

---

# 📈 Completion

<div align="center">

### Semester III PL/SQL Practical Progress

| Unit | Progress | Status |
|:---:|:---:|:---:|
| 🔵 **Unit 01** | `████████████████████` **100%** | ✅ Complete |
| 🟢 **Unit 02** | `████████████████████` **100%** | ✅ Complete |
| 🟠 **Unit 03** | `████████████████████` **100%** | ✅ Complete |

<br>

### 🟩 ALL UNITS COMPLETED

</div>

---

# 🎓 Learning Outcome

By completing these practicals, I practiced how to move from basic SQL and PL/SQL syntax toward **structured procedural database programming** — including decision making, iteration, exception handling, cursor-based processing and debugging.

```text
SQL
 ↓
PL/SQL Blocks
 ↓
Variables & Logic
 ↓
Control Structures
 ↓
Database Processing
 ↓
Cursors
 ↓
Parameterized Cursors
 ↓
Debugging & Problem Solving
```

---

<div align="center">

## 👨‍💻 Student

### **Nirav Vala**

**B.Sc. Information Technology · Semester III**  
**Roll No. 33 · LJ University**

<br>

> *Learning by building. Improving by debugging.*

<br>

<img src="https://img.shields.io/badge/PL%2FSQL-Practical%20Complete-16A34A?style=for-the-badge">
<img src="https://img.shields.io/badge/Semester-III-7C3AED?style=for-the-badge">

<br><br>

⭐ **Thanks for visiting this repository.**

</div>
