# Automated Internal Knowledge Workflow System - Development Update

## Overview

The team is developing an automated internal knowledge workflow system leveraging GPT-4 and integrating with tools like Slack, Notion, and Confluence. This system aims to extract and organize knowledge organically from existing communication channels, creating summaries, Q&A capabilities, and potentially micro knowledge bases. The initial focus is on functionality – enabling users to 'ask' and receive accurate responses – with operational and administrative features planned for later. A soft beta is targeted for mid-July, with a full rollout by the end of summer.

## Key Points

*   Developing an automated internal knowledge workflow system.
*   Leveraging GPT-4 and integrating with tools like Slack, Notion, and Confluence.
*   Focus on organic knowledge extraction and organization.
*   Prioritizing core functionality (Q&A) before ops/admin features.
*   Targeting a soft beta in mid-July and full rollout by the end of summer.

## Decisions Made

*   **LLM:** GPT-4 is the core Large Language Model (LLM).
*   **Backend:** NestJS was selected for the backend.
*   **Frontend:** Next.js & Tailwind were chosen for the frontend.
*   **Infrastructure:** AWS ECS, RDS, and Redis will be used for infrastructure.
*   **LLM Orchestration:** LangChain will be used for LLM orchestration.
*   **Chunk Size:** The chunk size for processing documents is capped at approximately 1.2K tokens.

## Action Items

*   [ ] **Review PRD:** Review the PRD on Notion (assignee: U03TE1JCU5D).
*   [ ] **Session Handling:** Consider and finalize session handling decisions.
*   [ ] **Prompt Patterns:** Solidify prompt patterns for optimal response generation.
*   [ ] **Prepare for Early Test Access:** Prepare for early test access next week.
*   [ ] **Provide feedback on the system.**
*   [ ] **Dev sprint kicks off next week.**

## Participants

*   U03TE1JCU5D

## Technical Details

*   **Architecture:** The system utilizes a three-tier architecture: Frontend (Next.js & Tailwind), Backend (NestJS), and Infrastructure (AWS ECS, RDS, Redis).
*   **LangChain Integration:** LangChain is used to manage the interaction with GPT-4, handle document loading and splitting, and orchestrate the overall workflow.
*   **Data Chunking:** Documents are split into chunks of approximately 1.2K tokens to optimize processing efficiency and context window limitations of GPT-4.
*   **Fine-Tuning:** Future plans include embedding tuning and history-based fine-tuning of GPT-4 to improve accuracy and relevance.

## Context

*   **PRD Location:** [Link to Notion PRD - To be added]

This system aims to reduce the time spent searching for information and improve knowledge sharing within the team.

## Tags

*   knowledge management
*   automation
*   AI
*   LLM
*   GPT-4
*   development
*   beta
*   internal tools
*   NestJS
*   Next.js
*   AWS
*   timeline