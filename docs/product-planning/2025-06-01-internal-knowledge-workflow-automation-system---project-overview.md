# Internal Knowledge Workflow Automation System - Project Overview

## Overview

This document outlines the development of a system designed to automate internal knowledge workflows. The system leverages existing communication tools (Slack, Notion, Confluence, Drive) and GPT-4 to create summaries, context-aware Q&A, and micro knowledge bases. The goal is to improve knowledge accessibility and reduce information silos within the organization.

## Key Decisions & Outcomes

*   **LLM Selection:** GPT-4 is the core Large Language Model (LLM) powering the system. Future plans include embedding tuning and history-based fine-tuning to improve accuracy and relevance.
*   **Tech Stack:**
    *   **Backend:** NestJS
    *   **Frontend:** Next.js & Tailwind
    *   **Infrastructure:** AWS ECS, RDS, Redis
    *   **LLM Orchestration:** LangChain
*   **Chunk Size:** Limited to approximately 1.2K tokens to optimize performance and context window.

## Timeline

*   **Soft Beta:** Mid-July
*   **Full Rollout:** End of Summer

## Action Items

| Task | Assignee | Status | Due Date | 
|---|---|---|---| 
| Review the Product Requirements Document (PRD) on Notion | U03TE1JCU5D | Open | ASAP | 
| Provide feedback on the system as it develops | U03TE1JCU5D | Open | Ongoing | 
| Prepare for a closed beta test | U03TE1JCU5D | Open | Next Week | 
| Continue development sprint | U03TE1JCU5D | Open | Next Week | 

## Current Focus

The immediate priority is enabling accurate question answering functionality.  This will form the foundation for subsequent features and enhancements.

## References

*   [Product Requirements Document (PRD) on Notion](link to Notion PRD - Placeholder)

## Participants

*   U03TE1JCU5D