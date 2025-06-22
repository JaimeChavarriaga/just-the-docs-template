# Plan for Interactive Learning Module: Introduction to Software Engineering

**Module Title:** Introduction to Software Engineering

**Target Audience:** Undergraduate software engineering students with basic knowledge in Java programming, SQL, UML, and database modeling.

**Learning Objectives:**

1.  Understand differences between programming and software engineering.
2.  Understand the differences in project-based and product-based mindsets.
3.  Describe technical tasks such as requirements elicitation, requirement analysis, design, coding, testing, and acceptance testing.
4.  Describe development workflows, where the developers take a feature or a bug, take the existing code, develop the corresponding item, and release it.
5.  Describe methods for project-based software development, such as UML, where all the software must be specified first and a complete set of iterations are proposed to build the software.
6.  Describe methods for product-based software development, such as agile methods and Scrum, where the team builds new iterations of the product based on user feedback and business objectives.

## Module Structure and Content Plan

### 1. Introduction (5-10 minutes)

*   **Content:**
    *   Hook: Start with a relatable scenario or question highlighting the difference between writing a small program and building a large, complex software system.
    *   What is Software Engineering? Define software engineering and its importance, emphasizing it's more than just coding.
    *   Module Objectives: Clearly state the learning objectives.
    *   Module Navigation: Explain how to navigate the module.
*   **Interactive Elements:**
    *   Poll/Question: Gauge initial understanding of software engineering vs. programming.

### 2. Programming vs. Software Engineering (15-20 minutes)

*   **Content:**
    *   Programming: Define programming and its focus.
    *   Software Engineering: Expand on the definition, highlighting aspects like large systems, teams, maintainability, scalability, security, reliability, and systematic approaches.
    *   Key Differences: Use a comparison table or diagram.
*   **Interactive Elements:**
    *   Drag-and-Drop Activity: Categorize tasks or characteristics.
    *   Short Quiz: Check understanding of distinctions.

### 3. Project-Based vs. Product-Based Mindsets (15-20 minutes)

*   **Content:**
    *   Project-Based Mindset: Define focus on project completion, defined scope, timeline, budget, and meeting initial requirements. Associate with traditional methodologies.
    *   Product-Based Mindset: Define focus on developing and evolving a product over time based on user needs and business goals, continuous improvement, iteration, and responsiveness. Associate with agile methodologies.
    *   Comparing the Mindsets: Discuss advantages, disadvantages, and appropriate use cases.
*   **Interactive Elements:**
    *   Scenario Analysis: Identify suitable mindset for given scenarios.
    *   Discussion Prompt: Reflect on prevalent mindset in the industry and why.

### 4. Technical Tasks in Software Engineering (20-30 minutes)

*   **Content:**
    *   Overview: Introduce technical tasks in the software development lifecycle.
    *   Requirements Elicitation: Definition, importance, techniques (interviews, surveys, workshops, observation).
    *   Requirements Analysis: Definition, importance, techniques (use cases, user stories, data flow diagrams).
    *   Design: Definition, importance, types (architectural, detailed), principles.
    *   Coding: Focus on clean code, standards, best practices, version control.
    *   Testing: Definition, importance, types (unit, integration, system, acceptance), TDD.
    *   Acceptance Testing: Definition, importance, role of stakeholders.
*   **Interactive Elements:**
    *   Matching Activity: Match tasks with descriptions or activities.
    *   Case Study: Identify technical tasks for a given scenario.

### 5. Development Workflows (15-20 minutes)

*   **Content:**
    *   Introduction: Explain how developers work on features or bugs.
    *   Workflow Steps: Describe a typical workflow (take item, understand, work with code, develop, code review, merge, release).
    *   Tools and Technologies: Briefly mention issue tracking, version control, CI/CD.
*   **Interactive Elements:**
    *   Interactive Diagram: Click on stages to learn more.
    *   Short Scenario: Identify steps for a developer working on a bug.

### 6. Project-Based Software Development Methods (15-20 minutes)

*   **Content:**
    *   Introduction: Explain project-based methodologies (upfront planning and specification).
    *   UML (Unified Modeling Language): Overview, purpose, brief introduction to common diagrams (class, use case, sequence), relevance in project-based development, emphasis on complete specification.
    *   Waterfall Model (Briefly): Mention as an example, highlighting sequential nature.
*   **Interactive Elements:**
    *   UML Diagram Recognition: Identify diagram types and representations.
    *   Drag-and-Drop: Arrange stages of a traditional project-based lifecycle.

### 7. Product-Based Software Development Methods (20-30 minutes)

*   **Content:**
    *   Introduction: Explain product-based methodologies (iterative, driven by feedback and objectives).
    *   Agile Principles: Introduce core values and principles of the Agile Manifesto.
    *   Scrum: Overview, roles (Product Owner, Scrum Master, Development Team), events (Sprint Planning, Daily Scrum, Sprint Review, Sprint Retrospective), artifacts (Product Backlog, Sprint Backlog, Increment), emphasis on iterative nature and feedback.
    *   Other Agile Methods (Briefly): Mention Kanban, Lean Software Development.
*   **Interactive Elements:**
    *   Matching Activity: Match Scrum elements with descriptions.
    *   Scenario-Based Questions: Apply understanding of agile principles or Scrum practices.
    *   Comparison Table: Compare project-based and product-based methodologies.

### 8. Conclusion (5-10 minutes)

*   **Content:**
    *   Summary of Key Concepts: Recap main topics.
    *   Relevance to Future Studies/Careers: Connect concepts to future learning and careers.
    *   Further Exploration: Provide resources.
    *   Call to Action: Encourage application of learned concepts.
*   **Interactive Elements:**
    *   Final Quiz: Assess overall understanding.
    *   Feedback Form: Allow students to provide feedback.

## Technical Considerations for a Browser-Based Module

*   **Platform:** Jekyll with Just the Docs theme for structure and content, incorporating interactive elements.
*   **Interactivity:** Use JavaScript for quizzes, drag-and-drop, interactive diagrams.
*   **Content Formatting:** Markdown for text, HTML for structure and interactive elements.
*   **Styling:** CSS for visual design.
*   **Responsiveness:** Ensure functionality on different devices.
*   **Accessibility:** Design with accessibility in mind (alt text, semantic HTML, keyboard navigation).