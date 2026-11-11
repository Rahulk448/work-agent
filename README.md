# Work Agent

Work Agent is a Python project for building an assistant that can pick up work across sessions. The goal is to keep project context, decisions, and next steps available as tasks move from one session to the next.

## Status

Early setup. The agent runtime and its first workflow are still to be built.

## Workspace

The local workspace uses `AGENTS.md` for working instructions and `MEMORY.md` for durable preferences, decisions, and open work. The `projects/` folder holds project files, and `notes/` holds working notes.

## First milestone

Build a Python command that reads a task and its project context, then records the outcome and next step so the next session can resume from that checkpoint.
