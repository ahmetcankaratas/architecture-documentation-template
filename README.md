# Architecture Documentation Template

A Markdown skeleton for a software architecture document: eight sections, each with the guiding questions it should answer.

| File                                                                               | Purpose                                                                              |
| ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| [`architecture-documentation-template.md`](architecture-documentation-template.md) | The skeleton — copy it into your repository as `docs/architecture.md` and fill it in |

## Structure

```
1. Introduction            Project context & document goals · System goals · Stakeholders
2. Architecture Drivers    Business goals · Key features · Quality attributes · Constraints
3. System Overview         Context delineation · Key terms and entities
4. System Decomposition    System structure · Data · Deployment and operation · Technology · Source code organization
5. Quality Concepts        One concept per quality driver: drivers & decisions · structural overview · behavior
6. Principles
7. Risks and Technical Debt
8. Glossary
```

## How to use

1. Copy the template next to the code and keep it under version control. It evolves with the system; it is not written once.
2. Define the scope first: who will read the document, and for what. A developer needs different things from a project lead.
3. Under each heading, answer the italic guiding questions, then delete them. Delete sections you have nothing to say about — an empty heading is worse than no heading.
4. Keep the document short enough to be read in one or two hours. It is a starting point for exploring the code, not a replacement for it.
5. Document drivers and decisions in their own files with the [Architecture Driver & Design Decision Templates](https://github.com/ahmetcankaratas/architecture-driver-template) and link them from sections 2 and 5.
