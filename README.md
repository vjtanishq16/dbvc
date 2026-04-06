# DBVC

**Git for Databases** — version control for your PostgreSQL schema.

DBVC is a Git-inspired version control system built specifically for relational databases.  
It brings familiar workflows like **commit, diff, log, and rollback** to database schema management.

---

## Why DBVC?

Every developer uses Git for code.  
But databases?

- Schema changes tracked manually.
- No clean rollback system.
- Other tools like feel heavy and complex.

**DBVC fixes this.**

It gives databases the same clean, developer friendly workflow as Git.

---

## Features 

- Git-like commands (`commit`, `log`, `diff`, `rollback`)
- Zero-config setup for PostgreSQL
- Human-readable schema diffs
- Reliable rollback mechanism
- Pure CLI — no UI, no server required
- CI/CD friendly

---

## Core Idea

DBVC tracks your database schema like Git tracks your code.

```bash
dbvc init
dbvc commit "Added users table"
dbvc diff
dbvc rollback