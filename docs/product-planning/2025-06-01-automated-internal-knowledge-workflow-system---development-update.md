# Automated Internal Knowledge Workflow System - Development Update

## Overview

This document summarizes the development progress of the automated internal knowledge workflow system. The system leverages GPT-4 and integrates with existing tools like Slack, Notion, and Confluence to streamline knowledge management and improve team efficiency. The goal is to evolve the system organically from existing team communication, providing summaries, Q&A capabilities, and potentially micro knowledge bases.

## Key Decisions and Outcomes

*   **Core LLM:** GPT-4 has been selected as the core Large Language Model (LLM) for the system. Future plans include embedding tuning and history-based fine-tuning.
*   **Technology Stack:** The following technologies are being utilized:
    *   **Backend:** NestJS
    *   **Frontend:** Next.js & Tailwind
    *   **Infrastructure:** AWS (ECS, RDS, Redis)
    *   **Framework:** LangChain
*   **Chunk Size:** The chunk size for processing data is limited to approximately 1.2K tokens to optimize performance and accuracy.

## Timeline

*   **Soft Beta:** Mid-July
*   **Full Rollout:** End of Summer

## Action Items

| Task | Assignee | Status |
|---|---|---|
| Review the Product Requirements Document (PRD) on Notion | U03TE1JCU5D | Open |
| Provide feedback on the system as it develops | U03TE1JCU5D | Open |
| Prepare for the development sprint kicking off next week | U03TE1JCU5D | Open |

## References

*   [Product Requirements Document (PRD) on Notion](link to Notion PRD - placeholder)

## Tags

*   knowledge management
*   automation
*   GPT-4
*   LLM
*   NestJS
*   Next.js
*   AWS
*   LangChain
*   beta
*   development