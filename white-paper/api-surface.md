# Computational Memory API Surface

The computational memory layer is accessed through a governed API surface. The API defines the allowed operations, the boundaries of each call, and the supervisory constraints that govern interaction with the persistence layer. All interactions with the memory layer must remain within non-advisory domains and must comply with retention, transformation, and access controls. The API surface consists of four calls that establish the only permitted interactions with the memory and persistence layers.

**Write Operations**  
Structured, bounded writes that store non advisory packets under explicit retention rules.

**Read Operations**  
Retrieval of previously retained structures without interpretation, evaluation, or personalized guidance.

**Transform Operations**  
Controlled transformations that remain analytical, non directional, and fully supervised.

**Delete Operations**  
Removal mechanisms governed by retention limits, supervisory controls, and compliance requirements.

The API surface provides the first standardized interface for safe continuity. It ensures that all interactions remain within non-advisory domains and that retained structures cannot be used to generate regulated outputs.

Computational memory is the foundation layer that supports decision systems, not a decision system itself.

_______________________

## Diagram Placeholder  
A diagram will be added here in v1.6 to illustrate the structure, boundaries, or flow described in this section.

## Cross‑Links

[Executive Summary](executive-summary.md)  
[Category Introduction](category-introduction.md)  
[Category Definition](category-definition.md)  
[Problem Context](/problem-statement/problem-context.md)  
[Solution](solution.md)  
[Taxonomy](taxonomy.md)  
[Reference Architecture](reference-architecture.md)  
[Governance Architecture](governance-architecture.md)  
[Operating Model](operating-model.md)  
[Implementation Path](implementation-path.md)  
[Enterprise Deployment Pattern](enterprise-deployment-pattern.md)  
[Regulated Boundaries Specification](regulated-boundaries-specification.md)  
[Supervised Persistence Contract](supervised-persistence-contract.md)  
[Supervised Continuity Test Suite](supervised-continuity-test-suite.md)  
[API Surface](api-surface.md)  
[Continuity Failure Modes](continuity-failure-modes.md)  
[Enterprise Controls Checklist](enterprise-controls-checklist.md)  
[Use Cases](use-cases.md)  
[Examples](/problem-statement/examples.md)  
[Vendor Implementation Architecture](vendor-implementation-architecture.md)  

_____________
**Attribution**  

This work defines the Nathan E. Myers AI Computational Memory Category.
Attribution to Nathan E. Myers is required for any use, adaptation, or derivative work under the CC BY 4.0 license.  

Required citation:
Nathan E. Myers, “AI Computational Memory Category,” 2026. https://nathanemyers-dev.github.io/ai-computational-memory/
