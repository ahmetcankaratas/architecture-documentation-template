# `<System name>` — Architecture Documentation

| | |
|---|---|
| **Version** | 0.1 |
| **Status** | Draft / In review / Released |
| **Owner** | Architect responsible for this document |
| **Last updated** | YYYY-MM-DD |

*Italic lines under each heading are guiding questions. Answer them, then delete them. A section that has nothing to say is deleted, not left empty.*

---

## 1. Introduction

*Set the scene. Create a basic understanding about the system.*

### 1.1 Project Context & Document Goals

*What is the main motivation for developing the system? Which business goals should be addressed? What are the key challenges? In which business context is the system embedded?*

- Project motivation
- Overall project goals
- Project strategy
- Document scope & goals

### 1.2 System Goals

*What is the basic solution idea for the system? What are the key functionalities? What are the key qualities? What makes the system useful?*

- Motivation for the system
- Basic information about the system and its goals
- References to detailed requirements documents
- Information about the system's environment

### 1.3 Stakeholders

*Who are the key stakeholders — internal and external, direct and indirect? What are their responsibilities? What are their main concerns for the system?*

| Stakeholder | Internal / External | Direct / Indirect | Responsibilities | Concerns |
|---|---|---|---|---|
| | | | | |

---

## 2. Architecture Drivers

*Provide an overview of the main architecture drivers. Each driver is documented with the [Architecture Driver Template](https://github.com/ahmetcankaratas/architecture-driver-template); this section summarizes them and links to the detailed driver files.*

### 2.1 Business Goals

*Which business goals should the architecture address?*

### 2.2 Key Features

*What are the main functionalities the system must provide? Which stakeholders benefit from which functionality? What architecture drivers exist for data? How should the system be operated?*

### 2.3 Quality Attributes

*What are the main quality attributes that drive the design of the architecture? How do these drivers manifest themselves in the system?*

### 2.4 Constraints

*What are the constraining factors that must be considered during development — technical, organizational, processual?*

---

## 3. System Overview

*Delineate the system from its context. Describe the key domain entities.*

### 3.1 Context Delineation

*How is the system embedded in its context? Which users (roles) use the system, and for which reason? With which other systems does it interact? How is it integrated with them and which data is exchanged?*

### 3.2 Key Terms and Entities

*What are the key entities of the business domain? What is their respective meaning? How are these entities related?*

---

## 4. System Decomposition

*What is the fundamental solution strategy for the system? What key decisions have been made, and why? How is the system decomposed — driven by functionality, data, deployment? What are the key technologies?*

### 4.1 System Structure

- Component overview
- Layering
- Platform / product relation

### 4.2 Data

- Data model
- Storages
- Data flow

### 4.3 Deployment and Operation

### 4.4 Technology Overview

### 4.5 Source Code Organization

---

## 5. Quality Concepts

*What are the key architecture solution concepts that address the quality drivers? Which decisions have been made that contribute to the fulfillment of these drivers? One sub-section per concept (security, scalability, multi-tenancy, availability, …), each with the same three parts.*

### 5.1 `<Concept name>` Concept

#### Drivers and Decisions

*Which drivers does this concept address? Which decisions implement it? Link the [Design Decision](https://github.com/ahmetcankaratas/architecture-driver-template) files.*

#### Structural Overview

*Which components, interfaces and data are involved, and how are they arranged?*

#### Behavior

*How does the concept work at runtime — sequences, states, failure handling?*

---

## 6. Principles

*Which design and implementation principles apply across the system (e.g. dependency rules, error handling, API conventions)?*

---

## 7. Risks and Technical Debt

*Where does technical debt exist? Which aspects need to be improved? Track points to improve.*

| ID | Description | Impact | Proposed action | Owner |
|---|---|---|---|---|
| | | | | |

---

## 8. Glossary

*Precisely define the key terms used in the project. What are they, and what do they mean?*

| Term | Meaning |
|---|---|
| | |
