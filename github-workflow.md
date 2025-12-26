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

    %% Researching - vertical list
    subgraph Research_Items[ ]
        direction TB
        R1[AI used before research]
        R2[Insufficient research - less time spent]
        R3[Content generated from scratch using prompts]
        R4[Only relying on guideline links for research]
    end
    R --> Research_Items

    %% Writing - vertical list
    subgraph Writing_Items[ ]
        direction TB
        W1[Writing independently without AI]
        W2[Writing with help from GPT]
        W3[Writing directly in Surfer]
    end
    W --> Writing_Items

    %% Editing - vertical list
    subgraph Editing_Items[ ]
        direction TB
        E1[Links embedded from GPT]
        E2[NLPs integrated with GPT]
        E3[Auto-optimized using Surfer]
    end
    E --> Editing_Items

    %% Submitting
    S --> F[Submit]


```

