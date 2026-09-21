# Agent World — Shared AI Workspace

This repository is the shared working area for the Agent World project.

## Purpose
AI model analyses, decisions, research notes, experiments and code-related material are stored here so participating models can read the same project context without repeatedly copying the same text between chats.

## Current canonical basis
The Agent World v3 Kanonik project document is the current architectural baseline. Earlier documents are historical references.

## Working rule
- A model may add analysis, critique, research or proposed changes.
- Analysis is input, not automatically a final decision.
- Decisions are recorded explicitly in DECISIONS/.
- The human project owner remains the final decision maker.
- Contradictions should be preserved and made explicit rather than silently overwritten.

## Suggested folders
- model-analysis/ — model-specific analyses
- decisions/ — accepted/rejected/open decisions
- research/ — external research and GitHub findings
- architecture/ — current architecture notes
- experiments/ — tests and experiments
- code/ — project source code when added

## Core loop
WORLD → OBSERVE → NEED → MISSION → AGENTS → MODELS → WORK → VERIFY → MEMORY/KNOWLEDGE/SKILL → EVALUATE → IMPROVE → WORLD vNEXT
