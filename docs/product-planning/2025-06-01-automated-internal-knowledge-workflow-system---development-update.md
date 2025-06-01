# Automated Internal Knowledge Workflow System - Development Update

## Overview

This document summarizes the development progress of an automated internal knowledge workflow system. The system leverages GPT-4 and other tools (Slack, Notion, Confluence, Google Drive) to process existing team communication, providing summaries, Q&A capabilities, and dynamic knowledge bases. The focus is on enabling users to simply 'ask' questions and receive accurate, context-aware answers. A soft beta is planned for mid-July, with a full rollout targeted for the end of summer. Feature scope is locked in, and a development sprint is commencing soon.

## Key Points

*   Automating internal knowledge workflows by processing existing team communication.
*   Leveraging GPT-4 as the core LLM, with plans for embedding tuning and history-based fine-tuning.
*   Focus on enabling users to 'ask' questions and receive accurate, context-aware answers.
*   Tech stack includes NestJS (backend), Next.js & Tailwind (frontend), AWS (ECS, RDS, Redis), and LangChain.
*   Feature scope is locked in.
*   Soft beta planned for mid-July, full rollout targeted for the end of summer.

## Decisions Made

*   **LLM:** GPT-4 is the core Large Language Model (LLM) for the system.
*   **Backend:** NestJS was selected for the backend.
*   **Frontend:** Next.js & Tailwind were chosen for the frontend.
*   **Infrastructure:** AWS ECS, RDS, and Redis will be used for infrastructure.
*   **LLM Orchestration:** LangChain will be used for LLM orchestration.
*   **Chunk Size:** The chunk size for LLM processing will be under ~1.2K tokens.

## Action Items

*   [ ] **Review PRD:** Review the rough PRD on Notion (assignee: U03TE1JCU5D).
*   [ ] **Provide Feedback:** Provide feedback on the system as it develops.
*   [ ] **Prepare for Sprint:** Prepare for the upcoming development sprint.

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
