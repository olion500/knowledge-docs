# Automated Internal Knowledge Workflow System - Development Update

## Overview

The team is developing an automated internal knowledge workflow system leveraging GPT-4 and other tools like Slack, Notion, and Confluence. The system aims to evolve organically from existing communication, providing summaries, Q&A capabilities, and potentially micro knowledge bases. This initiative aims to move away from manual documentation and improve knowledge accessibility for users.

## Key Points

*   Automating internal knowledge workflows to move away from manual documentation.
*   Leveraging existing communication tools (Slack, Notion, Confluence, Drive) for knowledge extraction.
*   GPT-4 is the core LLM, with plans for embedding tuning and history-based fine-tuning.
*   Tech stack includes NestJS (backend), Next.js & Tailwind (frontend), AWS (ECS, RDS, Redis), and LangChain.
*   Focus is on enabling users to 'ask' and receive accurate responses.
*   Soft beta planned for mid-July, full rollout by end of summer.

## Decisions Made

*   **LLM:** GPT-4 will be the core LLM.
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

## Tags

*   knowledge management
*   automation
*   LLM
*   GPT-4
*   NestJS
*   Next.js
*   AWS
*   LangChain
*   beta
*   internal tools