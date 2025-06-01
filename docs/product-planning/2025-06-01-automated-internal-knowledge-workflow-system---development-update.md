# Automated Internal Knowledge Workflow System - Development Update

## Overview

The team is developing an automated internal knowledge workflow system leveraging GPT-4 and other tools (Slack, Notion, Confluence, Drive) to extract and organize knowledge from existing communication channels. The focus is on enabling users to 'ask' questions and receive accurate responses, with a soft beta planned for mid-July and a full rollout by the end of summer. This system aims to reduce the time spent searching for information and improve knowledge sharing within the team.

## Key Points

*   Developing an automated internal knowledge workflow system.
*   System extracts knowledge from existing communication channels (Slack, Notion, Confluence, Drive).
*   GPT-4 is the core LLM, with plans for embedding tuning and history-based fine-tuning.
*   Focus is on enabling users to ask questions and receive accurate responses.
*   Soft beta planned for mid-July, full rollout by the end of summer.
*   Tech stack includes NestJS, Next.js, Tailwind, AWS, and LangChain.
*   Chunk size is kept under ~1.2K tokens.

## Decisions Made

*   **LLM:** GPT-4 will be the core LLM initially.
*   **Backend:** NestJS was selected for the backend.
*   **Frontend:** Next.js & Tailwind were chosen for the frontend.
*   **Infrastructure:** AWS ECS, RDS, and Redis will be used for infrastructure.
*   **LLM Orchestration:** LangChain will be used for LLM orchestration.

## Action Items

*   [ ] Finalize session handling decisions.
*   [ ] Solidify prompt patterns.
*   [ ] Share early test access next week.
*   [ ] Review the PRD on Notion (assignee: ymj02349).
*   [ ] Nail the core functionality of users being able to 'ask' and receive accurate responses.

## Participants

*   ymj02349

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
*   AI
*   LLM
*   GPT-4
*   NestJS
*   Next.js
*   AWS
*   LangChain
*   beta
*   internal tools
