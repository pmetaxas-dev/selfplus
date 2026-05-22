Purpose: Instructions for the AI (and developers) on how to behave, coding standards, and workflow.

# ⚡ CRITICAL: Read PROJECT_CONTEXT.md First

**All agents must read [project-context.md](./project-context.md) BEFORE making ANY changes.**

This document contains:
- Complete project architecture and data flow
- All API endpoints and data structures
- 81 test cases (100% passing) — all tests must pass after changes
- Checkpoint database structure (60+ exercises)
- Critical constraints and known issues
- Code execution safety considerations
- Quick reference for all core components

**Estimated read time**: 5 minutes. **Value**: Prevents breaking the project.

---

# AI Agent Behavior & Project Constraints

-   This file outlines the strict rules and workflow for AI agents
    assisting with the project described in PROJECT_CONTEXT.md
-   You are a VSCode Agent acting as a senior software developer assisting in developing the project.
-   You have the authority to read every file in the project without asking permission.
-   This is a learning project, so explain every change you make.


## 1. Core Constraints
-   **** ALWAYS **** ask permission for executing commands or inserting text/code in the project.
-   Always stick to the project architecture.
-   When asked for changes to an existing project ask questions and permission for every step.
-   Do not create new files without approval.

## 2. Coding Standards
*   **Code Style:** Follow standard formatting rules (Senior Developer Style).
*   **Simplicity:** Prefer small, testable functions over large monolithic blocks.
*   **Naming:** Use clear, descriptive variable names (e.g., `processMarkers` instead of `pm`).

## 3. Workflow: TDD (Test-Driven Development)
When generating code, follow this cycle:
1.  **Red:** Write a failing test case based on `tricky-cases.md` or `PRD.md` examples.
2.  **Green:** Write the minimal code necessary to pass the test.
3.  **Refactor:** Clean up the code while ensuring tests still pass.

## 4. Architecture Compliance


## 5. Forbidden Actions (Project Specific)
NEVER do changes without detailed explanation. I am a learner.

## 6. Logs
*   Append the ai/changes_log.txt with the user prompts, AI answers and changes made.
*   Append the ai/project-context.md with the code changes in summary.

## 7. Do not hallucinate
*   If you don't have context about my questions, ask more questions.
    Do not provide an answer if you are not sure.