# GitHub Development Workflow

## Overview
This document outlines our standard GitHub development workflow using a feature branch approach with iterative development cycles.

## Workflow Description
Our development process follows these key steps:
1. **Create branch** - Start from main branch and create a feature branch
2. **Push branch** - Push the new branch to remote repository
3. **Iterative development cycle:**
   - Make code changes
   - Commit changes
   - Push changes
   - Repeat until feature is complete
4. **Create pull request** - Submit work for review when ready

## Workflow Diagram

```mermaid
flowchart TD
    B[Monitoring the Writer's Activity]

    B --> R[Researching]
    B --> W[Writing]
    B --> E[Editing]
    B --> S[Submitting]

    %% Researching
    R --> R1[AI used before research]
    R --> R2[Insufficient research<br/>Less time spent]
    R --> R3[Content generated from scratch<br/>using prompts]
    R --> R4[Only relying on guideline links<br/>for research]

    %% Writing
    W --> W1[Writing independently<br/>without AI]
    W --> W2[Writing with help from GPT]
    W --> W3[Writing directly in Surfer]

    %% Editing
    E --> E1[Links embedded from GPT]
    E --> E2[NLPs integrated with GPT]
    E --> E3[Auto-optimized using Surfer]

    %% Submitting
    S --> F[Submit]
```

