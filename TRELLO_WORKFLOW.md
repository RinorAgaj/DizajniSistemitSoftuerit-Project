# Trello Workflow Documentation

This document outlines the Trello board structure and task management workflow for the project.

## Trello Board Structure

- **Lists**:
  1. Project Resources
  2. Backlog
  3. To Do
  4. In Progress
  5. Review
  6. Done

## Master Cards

- **Conceptual Model Tasks**: Contains checklists for building and documenting the conceptual model.
- **Software Architecture Document Tasks**: Tasks related to documenting the software architecture.
- **Detailed Design Document Tasks**: Focused on mid-level and low-level design models.
- **Implementation Tasks**: Tasks for Git setup, code refactoring, and applying architecture patterns.

## Master Cards - Details

### **1. Conceptual Model Tasks**

- Create a UML class diagram with 8–10 classes.
- Add attributes and annotate associations with multiplicities.
- Use aggregation for part-whole relationships and inheritance for kind-of relationships.
- Write a text description of the conceptual model:
  - Explain the concepts.
  - Justify relationships and design choices.

### **2. Software Architecture Document Tasks**

- Define the product vision, stakeholders, and target market.
- Develop static and dynamic architectural models for at least two modules:
  - Irrigation Layer
  - User Interface Layer
- Map relationships between models with tables and descriptions.
- Write architectural design rationale.
- Evaluate scenarios with a utility tree and describe one scenario in detail.

### **3. Detailed Design Document Tasks**

- Draft mid-level design models:
  - Create a mid-level static class diagram.
- Create low-level design models:
  - Include packages and operation specifications for a specific class.
- Map relationships between mid-level and low-level models.
- Write a detailed design rationale for design decisions.

### **4. Implementation Tasks**

- Set up the Git repository:
  - Initialize the repository and push the codebase.
  - Commit frequently to document progress.
- Translate the UML conceptual model into code.
- Apply at least one architecture style and two mid-level design patterns.
- Push all changes to GitHub and ensure the repository is accessible to the team.

## Task Assignment and Workflow

### **How Master Cards Translate Into Tasks**

Each master card is divided into smaller, actionable tasks, which are added to the **Backlog** list. Tasks are then moved across the workflow:

- **Backlog**: Contains all unstarted tasks.
- **To Do**: Tasks ready to be worked on.
- **In Progress**: Tasks currently being worked on by team members.
- **Review**: Completed tasks pending review for quality and adherence to requirements.
- **Done**: Tasks approved and completed.

### **Sprint Management**

Tasks are grouped into sprints to organize the workflow. Each sprint focuses on specific deliverables:

- **Sprint 1**: Set up the repository, Git workflow, and conceptual model.
- **Sprint 2**: Develop architectural models and document relationships.
- **Sprint 3**: Complete detailed design and refactor existing code.
- **Sprint 4**: Implement patterns, finalize documentation, and push code.

### Deadlines

- Each task assigned to the **To Do** list will include a deadline to ensure timely progress.
- Sprint deadlines will be reviewed and updated weekly in Trello.

## Team Members (Roles)

- **Rinor Agaj**: Manages Trello cards, oversees task management and can move cards to "Done.". Focuses on coding, and handles a significant portion of the documentation.
- **Azem Kazumi**: Primarily focuses on coding and assists with documentation when needed.
- **Agon Gashi**: Mainly focuses on documentation and provides support with coding tasks as needed.
