# Automated Internal Knowledge Workflow System - Development Update

## Overview

This document summarizes the development progress of an automated internal knowledge workflow system. The system leverages GPT-4 and other tools (Slack, Notion, Confluence) to process existing team communication, providing summaries, Q&A capabilities, and potentially micro knowledge bases. The goal is to evolve organically from existing team communication, making knowledge access seamless and intuitive for users. The system prioritizes a functional 'ask and answer' core before focusing on operations and administration.

## Key Points

*   Automating internal knowledge workflows using existing communication tools (Slack, Notion, Confluence).
*   Leveraging GPT-4 as the core LLM, with plans for embedding tuning and history-based fine-tuning.
*   Prioritizing a functional 'ask and answer' core before focusing on operations and administration.
*   Soft beta planned for mid-July, full rollout by end of summer.
*   Tech stack includes NestJS (backend), Next.js & Tailwind (frontend), AWS (ECS, RDS, Redis), and LangChain.

## Decisions Made

*   GPT-4 is the core LLM for the project.
*   NestJS, Next.js, Tailwind, AWS, and LangChain are the chosen technologies.
*   Chunk size will be kept under ~1.2K tokens.
*   Focus on 'ask and answer' functionality as the initial priority.

## Action Items

*   [ ] **Review PRD:** Review the PRD on Notion (assignee: U03TE1JCU5D).
*   [ ] **Session Handling:** Consider and finalize session handling decisions.
*   [ ] **Prompt Patterns:** Solidify prompt patterns for optimal response generation.
*   [ ] **Prepare for Early Test Access:** Prepare for early test access next week.

## Participants

*   U03TE1JCU5D
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
*   development
*   beta
*   internal tools
*   Slack
*   Notion
*   Confluence
*   AWS
*   LangChain