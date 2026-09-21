# Shared Model Workflow

1. Human gives a model result to ChatGPT.
2. ChatGPT records the source result in model-analysis/.
3. The next model receives the repository link and is asked to read the relevant files.
4. That model produces its analysis/code proposal.
5. Human brings that result back to ChatGPT.
6. ChatGPT records it, preserving the history.
7. Decisions are entered into decisions/ rather than being inferred from discussion.

## Pilot question
Can all participating models reliably read the same repository and work from the same files without manual copy/paste of the full analysis?
