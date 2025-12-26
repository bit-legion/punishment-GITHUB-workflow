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

    %% Researching - listicle style
    R --> RList["1. AI used before research<br/>2. Insufficient research - less time spent<br/>3. Content generated from scratch using prompts<br/>4. Only relying on guideline links for research"]

    %% Writing - listicle style
    W --> WList["1. Writing independently without AI<br/>2. Writing with help from GPT<br/>3. Writing directly in Surfer"]

    %% Editing - listicle style
    E --> EList["1. Links embedded from GPT<br/>2. NLPs integrated with GPT<br/>3. Auto-optimized using Surfer"]

    %% Submitting
    S --> F[Submit]

```

