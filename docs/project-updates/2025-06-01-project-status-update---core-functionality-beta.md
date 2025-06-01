# Project Status Update - Core Functionality Beta

## Overview

This document summarizes the current status of the project, focusing on the development of core functionality enabling users to ask questions and receive accurate responses. The project is progressing well, utilizing a modern tech stack and targeting a soft beta release in mid-July, with a full rollout (including a paid tier) planned before the end of summer. Early test access is expected next week.

## Key Points

*   **Backend:** Built using NestJS.
*   **Frontend:** Developed with Next.js and Tailwind CSS.
*   **Infrastructure:** Hosted on AWS utilizing ECS, RDS, and Redis.
*   **LLM Orchestration:** Leveraging LangChain (chunk size limited to < 1.2K tokens).
*   **Feature Scope:** Feature scope is currently locked in.
*   **Beta Timeline:** A soft beta is planned for mid-July.
*   **Full Rollout:** Target date for full rollout (including paid tier) is before the end of summer.
*   **Core Functionality:** The primary focus is on enabling users to ask questions and receive accurate responses.
*   **Product Requirements Document (PRD):** A rough PRD is available on Notion.

## Decisions Made

*   **Tech Stack Selection:** The following technologies were chosen:
    *   **Backend:** NestJS
    *   **Frontend:** Next.js and Tailwind CSS
    *   **Infrastructure:** AWS (ECS, RDS, Redis)
*   **LLM Orchestration:** LangChain was selected for managing and orchestrating Large Language Models.
*   **Chunk Size Limit:** A chunk size limit of approximately 1.2K tokens has been implemented for LLM processing.

## Action Items

*   **Share Early Test Access:**  Share early test access next week. (Assignee: ymj02349)
*   **Review PRD:** Review the Product Requirements Document (PRD) on Notion. (Assignee: ymj02349)
*   **Prompt Pattern Refinement:** Continue solidifying prompt patterns.

## Participants

*   ymj02349

## Technical Details

*   **Backend Framework:** NestJS provides a robust and scalable backend architecture.
*   **Frontend Framework:** Next.js enables server-side rendering and optimized performance. Tailwind CSS facilitates rapid UI development.
*   **Infrastructure Components:**
    *   **ECS:**  Amazon Elastic Container Service for container orchestration.
    *   **RDS:** Amazon Relational Database Service for database management.
    *   **Redis:** In-memory data store for caching and session management.
*   **LLM Integration:** LangChain is used to manage prompts, chain multiple LLM calls, and handle data retrieval.
*   **Token Chunking:**  The LLM input is chunked into segments of approximately 1.2K tokens to manage context window limitations.

## Context

*   **PRD Location:** [Link to Notion PRD - Placeholder] (Replace with actual link)

## Tags

*   #nestjs
*   #nextjs
*   #tailwind
*   #aws
*   #langchain
*   #llm
*   #prd
*   #beta
