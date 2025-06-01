# Automated Internal Knowledge Workflow System - Development Update

## Overview

This document summarizes the development progress of an automated internal knowledge workflow system. The system leverages GPT-4 and other tools (Slack, Notion, Confluence) to process existing team communication, providing summaries, Q&A capabilities, and potentially micro knowledge bases. The goal is to create dynamic knowledge bases and Q&A functionality, moving away from manual documentation. The project is in early development with a soft beta planned for mid-July and a full rollout targeted for the end of summer.

## Key Points

*   Automating internal knowledge workflows using existing communication tools.
*   Leveraging GPT-4 as the core technology, with plans for embedding tuning and history-based fine-tuning.
*   Technical stack includes NestJS (backend), Next.js & Tailwind (frontend), AWS (ECS, RDS, Redis), and LangChain.
*   Focus on enabling users to simply 'ask' and receive accurate responses.
*   Soft beta planned for mid-July, full rollout before the end of summer.
*   Ops/admin functionality is currently on hold to prioritize core functionality.

## Decisions Made

*   **LLM:** GPT-4 will be the core LLM.
*   **Backend:** NestJS was selected for the backend.
*   **Frontend:** Next.js & Tailwind were chosen for the frontend.
*   **Infrastructure:** AWS ECS, RDS, and Redis will be used for infrastructure.
*   **LLM Orchestration:** LangChain will be used for LLM orchestration.
*   **Chunk Size:** The chunk size for processing documents is capped at approximately 1.2K tokens.

## Action Items

*   [ ] Review the PRD on Notion.
*   [ ] Provide feedback on the project.
*   [ ] Prepare for closed beta testing in mid-July.
*   [ ] Finalize session handling decisions.

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

*   AI
*   Knowledge Management
*   Automation
*   GPT-4
*   LangChain
*   NestJS
*   Next.js
*   AWS
*   Beta Testing
