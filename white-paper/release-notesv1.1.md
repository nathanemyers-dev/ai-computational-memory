# Version 1.1 Release Notes  
Version 1.1 moves the category from definition to implementation. It introduces the computational memory API surface and the supervised persistence contract, establishing the formal interface and governance boundaries required for safe, predictable, enterprise‑grade retention. These artifacts define how systems write, read, transform, and delete retained structures under supervised constraints, and they specify the obligations and controls required for any system interacting with computational memory. Version 1.1 operationalizes the category by providing the technical and supervisory scaffolding needed for compliant persistence.

**Scope**  
Version 1.1 introduces the first operational interfaces for computational memory. It adds the API surface and the supervised persistence contract that define how systems interact with the persistence layer under governance.

**Completed**  
Computational memory API surface defined  (white-paper/api-surface.md)  
Supervised persistence contract established  (white-paper/supervised-persistence-contract.md)  
Operational boundaries formalized
Interaction rules documented
Governance checkpoints mapped to API operations
Retention, transformation, and access constraints integrated into the contract
Version routing updated

**Out of Scope**  
Model code
SDK integration
Enterprise deployment templates
Reference implementations
Cross system orchestration
Runtime supervision engines
Decision architecture components

**Additions**  
Version 1.1 introduces the computational memory API surface. The API defines the allowed operations for writing, reading, transforming, and deleting retained structures under explicit governance. It provides the first standardized interface for safe continuity.

Version 1.1 also introduces the supervised persistence contract. The contract defines the obligations, constraints, and supervisory controls required for any system that interacts with computational memory. It ensures that all operations remain non advisory and that no retained structure can form advisory state.

**Future Additions**  
Version 1.2 will introduce the enterprise deployment pattern and the reference architecture for supervised continuity.

**Outcome**  
Version 1.1 moves the category from definition to implementation. It provides the operational interfaces required for safe persistence and establishes the supervised contract that governs all interactions with computational memory.


________________

**Attribution**  
This work defines the Nathan E. Myers AI Computational Memory Category. Attribution to Nathan E. Myers is required for any use, adaptation, or derivative work under the CC BY 4.0 license.

Required citation: Nathan E. Myers, “AI Computational Memory Category,” 2026. https://nathanemyers-dev.github.io/ai-computational-memory/
