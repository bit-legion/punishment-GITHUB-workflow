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
    A[Start: Main Branch] --> B[Create Feature Branch]
    B --> C[Push Branch to Remote]
    C --> D[Make Code Changes]
    D --> E[Commit Changes]
    E --> F[Push Changes]
    F --> G{More Changes Needed?}
    G -->|Yes| D
    G -->|No| H[Create Pull Request]
    H --> I[Code Review]
    I --> J{Review Approved?}
    J -->|No - Changes Requested| K[Address Review Comments]
    K --> D
    J -->|Yes| L[Merge to Main Branch]
    L --> M[Delete Feature Branch]
    M --> N[End]

    style A fill:#e1f5fe
    style H fill:#fff3e0
    style L fill:#e8f5e8
    style N fill:#fce4ec
```

