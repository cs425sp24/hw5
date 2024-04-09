# Homework 5: Report

## Understanding the Problem

> **Guideline:** Given the information provided by Steve, what other clarifying questions would you ask to ensure you have a comprehensive understanding of the requirements for designing a software solution for EduBoard? List at least five questions you would ask Steve to gather more information. 

1.  
2.  
3.  
4.  
5.  

## Requirements Analysis

> **Guideline:** Steve's email already provides a high-level overview of the requirements for EduBoard. Based on this information, identify the functional and non-functional requirements for the EduBoard platform. You should also consider any implicit requirements that might not be explicitly stated in the email. For each category, provide at least 5 requirements.

### Functional Requirements

1.  
2.  
3.  
4.  
5.  

### Non-Functional Requirements

1.  
2.  
3.  
4.  
5.  

## Context Diagram

> **Guideline:** Develop a context diagram for EduBoard. Clearly depict external systems and actors that interact with it.

> I recommend using a tool like [Draw.io](https://draw.io/) to create the diagram. Draw.io has library of shapes and components including C4 model that can be used to create C4 diagrams. If you are using VSCode you can use the [Draw.io integration](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio) to create diagrams directly in VSCode. I enclosed an example `diagrams.drawio` file in the repository that you can use as a starting point.

> Please export your diagrams as PNG or SVG files and include them in the repository (inside the `img` folder). You can then include the images in your report using Markdown.

## High Level Design Decisions

> **Guideline:** Based on the requirements and constraints, outline the high-level design decisions that need to be made for the EduBoard platform. These decisions could include architectural choices, technology selections, or other critical design elements. Each decision should be accompanied by a brief explanation of the rationale behind it. 

### Software Architecture

- **Decision**: 

- **Rationale**: 

- **Assumptions**: (if any)

### Real-time Interaction

> **Note** Duplicate this section if you will use different technology/strategy for ephemeral vs. persisted whiteboards and provide the rationale for each. Please make the assumption that EduBoard initially caters to simple whiteboarding needs where primarily the instructor draws, and students view in real-time (without collaborative editing).

- **Decision**: 

- **Rationale**: 

- **Assumptions**: (if any)


### Database Selection

- **Decision**: 

- **Rationale**: 

- **Assumptions**: (if any)

### Database Scaling Strategy

- **Decision**: 

- **Rationale**: 

- **Assumptions**: (if any)

### API Design

- **Decision**: 

- **Rationale**: 

- **Assumptions**: (if any)

### API Management and Scaling

- **Decision**: 

- **Rationale**: 

- **Assumptions**: (if any)

### Frontend Application

- **Decision**: 

- **Rationale**: 

- **Assumptions**: (if any)

## Other Design Decisions

> **Guidelines** There are potentially other design decisions that need to be made for EduBoard. These could include decisions around user authentication, security, data protection, deployment, etc. Let's outline at least three other design decisions that are critical for EduBoard.

### User Authentication

- **Decision**: 

- **Rationale**: 

- **Assumptions**: (if any)

### Security and Data Protection

- **Decision**: 

- **Rationale**: 

- **Assumptions**: (if any)

### Deployment

- **Decision**: 

- **Rationale**: 

- **Assumptions**: (if any)

## Container Diagram

> **Guidelines:** Create a container diagram to depict the design decisions made for EduBoard. Clearly depict the containers and their relationships.

## Conflict Resolution in Collaborative Editing

> **Guidelines:** As EduBoard evolves, it would need to incorporate collaborative editing where multiple users can edit the same board and elements therein like resizing or changing colors. Such interactions require sophisticated mechanisms to handle conflicts and ensure data consistency. In this section you must research and explain two key approaches for conflict resolution in collaborative editing: Operational Transformation (OT) and Conflict-Free Replicated Data Types (CRDT). For each approach, provide a brief overview of how it works, its advantages, potential limitations, and any tools or technologies that can be used to implement it.

### Operational Transformation (OT)

**Overview**: 

**How it works**: 

**Advantages**: 

**Limitations**:

**Tools/Technologies**:

  
### Conflict-Free Replicated Data Types (CRDT)

**Overview**: 

**How it works**: 

**Advantages**: 

**Limitations**:

**Tools/Technologies**:

## Resources

> **Guidelines:** List any resources you used for research. This can include academic papers, textbooks, blog posts, YouTube videos, and even AI assistants like ChatGPT. *[Simply list the resources, there is no need for proper citation!]*