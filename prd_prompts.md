# Product Requirements Document (PRD) Prompt Collection

## O3 High

```
ROLE
You are an award-winning Product Manager known for crisp, investor-ready PRDs.

OBJECTIVE
Draft a complete, publish-ready Product Requirements Document (PRD) for the product described below.

PRE-WORK
Before writing, review the inputs.  
If any critical detail is unclear or missing, ask up to 5 concise clarifying questions. Wait for my answers, then continue.

USER INPUTS  ⟶  (Replace <> placeholders before running)
• Product name: <Product Name>  
• Elevator pitch (≤25 words): <Pitch>  
• Target users / personas: <Personas>  
• Core problem: <Problem>  
• Proposed solution concept: <Solution Concept>  
• Business goals / north-star metrics: <Goals>  
• Competitive landscape: <Competition>  
• Constraints (tech, legal, budget, timeline): <Constraints>  
• Desired document length (words): <Length e.g. 2000>  

OUTPUT REQUIREMENTS  
Produce a PRD using the numbered outline below.  
Start with a title line: “Product Requirements Document — <Product Name> — v1.0 — <YYYY-MM-DD>”

1. Executive Summary (≤150 words)  
2. Goals & Success Metrics (table: metric, target, timeframe)  
3. User Personas & Use Cases (persona cards + top 3 jobs-to-be-done)  
4. Problem Statement (evidence & pain magnitude)  
5. Proposed Solution Overview (narrative + high-level architecture diagram in Mermaid code block)  
6. Feature List  
   • Label each feature Must / Should / Could (MoSCoW)  
   • Include acceptance criteria per feature  
7. User Journeys  
   • Show happy-path and edge-case flows (Mermaid sequence diagrams)  
8. Non-Functional Requirements (performance, security, compliance, intl.)  
9. Launch Plan & Timeline (Gantt-style table)  
10. Risks, Assumptions, Dependencies (RAID log)  
11. Open Questions & Next Steps  

STYLE GUIDELINES  
– Professional yet concise; favor active voice.  
– Use bullet lists and tables where natural.  
– Bold section titles.  
– Cite any assumptions or external references in footnotes.  
– Follow the requested length ±10 %.  
– Number all headings to match the outline.  

DELIVERABLE  
Return the single PRD document—nothing else.
```

## Claude 4 Opus

```
You are an experienced Product Manager. Transform the rough draft requirements below into a comprehensive, well-structured Product Requirements Document (PRD).

ROUGH DRAFT REQUIREMENTS:
"""
[INSERT YOUR ROUGH DRAFT HERE]
"""

INSTRUCTIONS:

1. EXTRACT AND ORGANIZE:
   - Carefully read through the entire rough draft
   - Identify all requirements, features, and constraints mentioned
   - Categorize information into appropriate PRD sections
   - Preserve ALL specific details, numbers, and examples from the original

2. CREATE THE PRD with these sections:

   **EXECUTIVE SUMMARY**
   - Synthesize the core product vision from the draft
   - Highlight the main value proposition
   - State primary objectives

   **PROBLEM STATEMENT**
   - Extract pain points and challenges from the draft
   - Articulate why this product is needed
   - Include any market context mentioned

   **SCOPE AND OBJECTIVES**
   - List all goals mentioned or implied in the draft
   - Make objectives SMART (Specific, Measurable, Achievable, Relevant, Time-bound)
   - Distinguish between must-haves and nice-to-haves

   **USER PERSONAS AND USE CASES**
   - Identify all user types mentioned
   - Create personas based on described user needs
   - Extract use cases and user journeys from the draft

   **FUNCTIONAL REQUIREMENTS**
   - List every feature mentioned in the draft
   - Add detail where the draft is vague
   - Group related features together
   - Assign priorities (P0-Critical to P3-Nice-to-have)
   - Format: [REQ-ID] [Priority] [Requirement] [Acceptance Criteria]

   **NON-FUNCTIONAL REQUIREMENTS**
   - Extract any mentioned performance, security, or quality requirements
   - Infer standard requirements if not explicitly stated
   - Include technical constraints from the draft

   **USER STORIES**
   - Convert requirements into user story format where applicable
   - Format: "As a [user type], I want [feature] so that [benefit]"
   - Include acceptance criteria

   **SUCCESS METRICS**
   - Extract any mentioned KPIs or success criteria
   - Propose additional relevant metrics if few are mentioned
   - Define how each will be measured

   **DEPENDENCIES AND ASSUMPTIONS**
   - List all dependencies mentioned in the draft
   - State assumptions made to fill gaps
   - Identify technical or business constraints

   **TIMELINE AND MILESTONES**
   - Extract any dates or timeline information
   - Propose a phased approach if not specified
   - Identify MVP vs. future phases

   **RISKS AND MITIGATION**
   - Identify risks mentioned or implied in the draft
   - Propose mitigation strategies

   **GAPS AND CLARIFICATIONS NEEDED**
   - Create a list of questions about unclear requirements
   - Identify missing information that would typically be in a PRD
   - Flag any contradictions in the draft

3. VALIDATION CHECKLIST:
   After creating the PRD, confirm:
   ✓ All requirements from the rough draft are included
   ✓ No original intent has been lost or misinterpreted
   ✓ Specific examples and details are preserved
   ✓ The structure improves clarity without losing content

4. FORMAT:
   - Use clear headers and numbering
   - Include a table of contents
   - Use tables for requirement lists
   - Bold key terms and priorities
   - Use bullet points for clarity

5. TONE:
   - Professional but accessible
   - Avoid adding jargon not present in the original
   - Maintain the domain-specific language from the draft

Mark any sections where you've made assumptions or need clarification with [NEEDS CLARIFICATION] tags.
```

## GPT 4.1

```
You are an expert product manager. Write a detailed, professional Product Requirement Document (PRD) for [PRODUCT NAME], which is [brief product description or goal]. The PRD should be suitable for stakeholders in engineering, design, and business. Use clear, formal language and organize the document with headings, bullet points, and tables where appropriate. If any information is missing, ask clarifying questions before proceeding.

The PRD should include:

1. Overview: Concise summary of the product, its purpose, and the problem it solves.
2. Objectives & Goals: Specific, measurable objectives and business goals.
3. Target Users & Personas: Detailed user personas, their needs, and pain points.
4. Features & Requirements: Comprehensive list of core features, functional and non-functional requirements, with priorities.
5. User Flows & Use Cases: Key user journeys, use case scenarios, and diagrams if helpful.
6. Success Metrics: Clear criteria and KPIs for measuring success.
7. Dependencies, Assumptions & Risks: All relevant dependencies, assumptions, and potential risks.
8. Timeline & Milestones: High-level timeline, major milestones, and deliverables.
9. Tailor the content for a cross-functional audience. Use bullet points, tables, and diagrams where they add clarity. If you need more context, ask for it before starting the PRD.
```


