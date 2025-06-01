# Automated Internal Knowledge Workflow System - Project Overview

## Overview

This document outlines the development of an automated internal knowledge workflow system leveraging GPT-4 and integrating with existing tools like Slack, Notion, and Confluence. The system aims to organically evolve from existing team communication, providing summaries, Q&A functionality, and potentially team-level knowledge bases. The initial focus is on ensuring accurate responses to user queries.

## Key Decisions & Outcomes

*   **Core LLM:** GPT-4 is the primary Large Language Model (LLM) powering the system.
*   **Backend:** NestJS is used for the backend infrastructure.
*   **Frontend:** The frontend is built using Next.js and Tailwind.
*   **Infrastructure:** The system is deployed on AWS utilizing ECS, RDS, and Redis.
*   **LLM Orchestration:** LangChain is employed for LLM orchestration.
*   **Chunk Size:** Text chunks are limited to approximately 1.2K tokens to optimize performance.

## Action Items

| Task | Assignee | Status | 
|---|---|---|
| Review the Product Requirements Document (PRD) on Notion | U03TE1JCU5D | Open |
| Provide feedback on the system | U03TE1JCU5D | Open |
| Development sprint kicks off next week |  | In Progress |

## Timeline

*   **Soft Beta:** Mid-July
*   **Full Rollout:** End of Summer

## Participants

*   U03TE1JCU5D

## References

*   [Product Requirements Document (PRD) on Notion](link to Notion PRD - *replace with actual link*)
