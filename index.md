**AI Computational Memory**

AI computational memory is the governed persistence layer that enables continuity, structured reuse, and supervised retention across interactions without entering advisory domains. It provides the foundation for predictable behavior and enterprise scale modeling.

**Why this matters**

AI systems have the technical ability to maintain continuity, but vendors force a full reset every session because retained memory can be classified as advisory activity under current regulatory rules. This creates a structural problem. The system must prevent the formation of advisory state, not only advisory output. As a result, memory can fail silently even when no advisory warning is shown.

There are three independent reasons why continuity breaks. Advisory guardrails prevent the system from retaining information that could later produce regulated guidance. Retention eligibility rules reject packets that are not identity, preference, or long term relevant. Interpretation heuristics classify some packets as conversational or instruction-like and drop them to avoid forming durable state. These gates operate at the memory boundary, so failures do not surface warnings. This is why users experience continuity loss even when they are not asking for advice. 

Computational memory is the foundation layer that supports decision systems, not a decision system itself.  

The aim of this work is to establish a formal category for supervised AI persistence so regulators, governance teams, practitioners, and engineers can align on a safe continuity layer that does not fall under advisory guardrails. The goal is to create consensus and drive the regulatory carve out needed for AI systems to maintain structured state and operate as intended without forcing users off platform.  

**Examples:**

"When I build a model to evaluate an exit stock price, AI triggers advisory guardrails even though I am not asking it to make a decision. I only need continuity so I can adjust inputs and compare outcomes."

"When I create long-term financial plans, AI cannot retain my assumptions or prior calculations. Each session starts from zero, which forces me to rebuild the entire model every time."

"When I track job search workflows, AI cannot remember prior applications or recruiter interactions. I have to restate the entire context in every session, which breaks repeatability."

These examples show why industry and regulators need a defined category for safe continuity so AI can operate efficiently without crossing compliance lines. AI computational memory provides that category by separating safe persistence from advisory activity and defining the rules for supervised retention.

**White Paper**

The white paper defines the full governance architecture, operating model, implementation path, regulatory alignment, and use cases for computational memory.

[solution](white-paper/solution.md)  
[governance-architecture](white-paper/governance-architecture.md)  
[operating-model](white-paper/operating-model.md)  
[implementation-path](white-paper/implementation-path.md)  
[regulatory-alignment](white-paper/regulatory-alignment.md)  
[use-cases](white-paper/use-cases.md)  
[api-surface](white-paper/api-surface.md)  
[supervised-persistence-contract](white-paper/supervised-persistence-contract.md)  
[FAQ](white-paper/FAQ.md)  

**Category Materials:**

[problem-statement](problem-statement/index.md)  
[category-definition](category-definition/index.md)  

**Outcome**  

This site provides the complete category definition and technical specification for AI computational memory. It establishes the rules, boundaries, and supervisory controls required for safe persistence in enterprise AI systems.

**Version History**  

- **Version 1.0** established the complete conceptual and governance foundation for AI computational memory.  
- **Version 1.1** introduced the computational memory API surface and the supervised persistence contract, moving the category from definition to implementation.


_____________
**Attribution**

This work defines the Nathan E. Myers AI Computational Memory Category. 
Attribution to Nathan E. Myers is required for any use, adaptation, or derivative work under the CC BY 4.0 license.

See the README for required citation format: 
[README](README1.md)
