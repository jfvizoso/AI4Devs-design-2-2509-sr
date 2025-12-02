# Prompts for LTI ATS Design

## 1. User Stories Generation

**Prompt:**
> Act as a Product Manager and Business Analyst. Using the LTI PRD (provided below), generate at least 3 User Stories for the "AI-Driven Sourcing & Screening" module.
>
> **Context:** LTI is an AI-native ATS.
> **Format:** Use the following template for each User Story:
> - **Title:** [User Story Title]
> - **As a:** [Role]
> - **I want to:** [Action]
> - **So that:** [Benefit]
> - **Acceptance Criteria:**
>   - [ ] Criterion 1
>   - [ ] Criterion 2
>
> **PRD Content:**
> [Insert relevant sections from LTI-JFV.md here, specifically Section 4.A and Use Case 1]

## 2. Product Backlog Generation

**Experiment 1: Standard Prioritization**
> Act as a Product Owner. Take the User Stories generated above and create a Product Backlog. Prioritize them based on business value and dependency. Present the backlog as a table with columns: ID, Title, Priority (High/Medium/Low), and Rationale.

**Experiment 2: MoSCoW Method**
> Act as a Product Owner. Take the User Stories generated above and organize them into a Product Backlog using the MoSCoW method (Must have, Should have, Could have, Won't have). Explain why each story falls into its category.

**Experiment 3: Value vs. Effort**
> Act as a Product Owner. Estimate the relative value and effort for the User Stories (High/Medium/Low). Create a backlog that prioritizes "Quick Wins" (High Value, Low Effort) first. Present the result in a matrix or list format.

**Winner & Rationale:**
> [User to fill in: Which prompt worked best and why?]

## 3. Work Tickets Generation

**Prompt:**
> Act as a Technical Lead. Take the User Story "[Insert Selected Story Title]" and break it down into technical work tickets.
>
> **Requirements:**
> - Create separate tickets for Frontend, Backend, and Database tasks if applicable.
> - Include a "Definition of Done" for each ticket.
> - Mention specific technologies from the stack (React, Node.js, PostgreSQL, Pinecone).
>
> **Output Format:**
> - **Ticket ID:** [e.g., LTI-101]
> - **Title:** [Ticket Name]
> - **Description:** [Technical details]
> - **Type:** [Frontend/Backend/DB/DevOps]
> - **Acceptance Criteria:** [List]

## 4. Effort Estimation

**Prompt:**
> Act as a Scrum Master and Dev Team. Estimate the effort for the work tickets generated above.
>
> **Methodology:** Planning Poker (Fibonacci sequence: 1, 2, 3, 5, 8, 13, 21).
> **Units:** Story Points.
>
> **Output:**
> Provide a table with Ticket ID, Title, and Estimated Points. Briefly explain the reasoning for the complexity score (e.g., "5 points due to complex integration with OpenAI API").
