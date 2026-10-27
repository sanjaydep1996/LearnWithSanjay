# Episode 04: AI Output Verification & Risk Gates (AST Test-Gap)

In this episode, we build an automated verification engine that catches AI code hallucination and untested modifications before PR merge.

## Key Concepts
1. **AST Test-Gap Detection**: Comparing modified abstract syntax trees of source code files against test file changes.
2. **Deterministic Risk Gates**: Flagging destructive DDL (`DROP TABLE`, unindexed foreign keys) and security risks (`origin: *`, weak crypto) with zero LLM latency.
3. **Local SQLite Decision Logging**: Tracking human-in-the-loop acceptance (`accept | edit | reject`) to calculate real AI ROI.
