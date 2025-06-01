# Automated Internal Knowledge Workflow System - Development Update

## Overview

This document summarizes the development progress of an automated internal knowledge workflow system. The system leverages GPT-4 and other tools (Slack, Notion, Confluence) to process existing team communication, providing summaries, Q&A capabilities, and potentially micro knowledge bases. The goal is to evolve organically from existing team communication, making knowledge access seamless and intuitive for users.

## Key Points

*   The system is automating internal knowledge workflows by processing existing communication channels.
*   GPT-4 is the core technology, with plans for embedding tuning and history-based fine-tuning.
*   The system focuses on enabling users to simply 'ask' and receive accurate responses.
*   A soft beta is planned for mid-July, with a full rollout targeted for the end of summer.
*   The Product Requirements Document (PRD) is located on Notion (link to be added).

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

## Participants

*   U03TE1JCU5D

## Technical Details

*   **Architecture:** The system utilizes a three-tier architecture: Frontend (Next.js & Tailwind), Backend (NestJS), and Infrastructure (AWS ECS, RDS, Redis).
*   **LangChain Integration:** LangChain is used to manage the interaction with GPT-4, handle document loading and splitting, and orchestrate the overall workflow.
*   **Data Chunking:** Documents are split into chunks of approximately 1.2K tokens to optimize processing efficiency and context window limitations of GPT-4.
*   **Fine-Tuning:** Future plans include embedding tuning and history-based fine-tuning of GPT-4 to improve accuracy and relevance.

## Context

*   **PRD Location:** [Link to Notion PRD - To be added]
*   This system aims to reduce the time spent searching for information and improve knowledge sharing within the team.

## Tags

*   knowledge management
*   automation
*   AI
*   LLM
*   GPT-4
*   development
*   beta
*   internal tools