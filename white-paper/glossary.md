# Glossary

Below is the governed terminology for the AI Computational Memory Category.
Each term defines a formal construct used across the white paper, regulatory artifacts, and deployment pattern.

| Term | Definition |
| --- | --- |
| advisory activity | Activity in which an AI system generates, shapes, or influences a user’s decision, judgment, or course of action in a way that regulators classify as guidance. Advisory activity includes any output that interprets user intent, recommends actions, evaluates choices, or produces directionally suggestive conclusions. Computational memory must never form or enable advisory activity; it operates strictly as a continuity layer, not a decision or guidance surface. |
| advisory guardrails | Regulatory controls that prevent AI systems from producing guidance, recommendations, evaluations, or directionally suggestive outputs. These guardrails operate at both the output layer and the memory boundary. |
| advisory-state | A prohibited condition in which retained packets or transformations imply guidance, suitability, direction, or decision‑making. Any retained structure that could later produce advisory activity. Advisory state is prohibited; computational memory must enforce boundaries that prevent its formation. |  
| advisory-state prevention gate | A supervised control that rejects packets or transformations that would create advisory state. |
| analytical persistence | The governed ability to maintain structured, non‑advisory analytical state across interactions. Analytical persistence supports modeling, workflows, and assumptions without entering advisory domains or triggering regulated guidance. |
| analytical surface | The stable, repeatable interface through which users perform structured analysis. Computational memory supports the analytical surface without influencing decisions. |
| audit surface | The complete set of logs, decisions, classifications, and supervisory events required for regulatory and enterprise review. The governed visibility layer that exposes retention events, supervisory actions, and continuity operations for compliance review. |
| boundary-layer activation | The moment when a retention or supervisory rule is triggered at the memory boundary, determining whether a packet is eligible for safe persistence. |
| category spine | The conceptual backbone of the AI Computational Memory Category, including definition, problem context, solution, governance architecture, operating model, and deployment pattern. |
| classification gates | The heuristics that classify packets as identity, preference, conversational, instruction-like, or advisory-risk, determining whether they can be retained. |
| classification outcome | The result of evaluating a packet or transformation against retention and advisory boundaries. |
| compliant persistence layer | The governed persistence layer that satisfies regulatory requirements for non-advisory operation, ensuring that retained structures support continuity without being classified as guidance or advisory state. |
| computational artifacts | Retained, non-advisory structures created through supervised continuity operations that support reuse and stability without forming advisory state. A non‑advisory packet produced by computation, transformation, or continuity operations |
| computational memory | The governed persistence layer that enables continuity, structured reuse, and supervised retention across interactions without entering advisory domains. |
| computational memory surface | The governed layer within AI decision infrastructure where continuity, structured reuse, and supervised retention occur. The computational memory surface provides the stable, non‑advisory foundation for maintaining analytical state across interactions and ensures that retained structures cannot produce guidance or advisory activity. |
| conversational packets | Transient dialogue packets classified as non-durable and ineligible for retention because they do not contribute to safe, structured continuity. |
| continuity | The ability of an AI system to maintain structured, non-advisory state across interactions under governed constraints. |
| continuity failure modes | The defined set of conditions under which continuity breaks, including guardrail activation, retention-eligibility rejection, and heuristic misclassification. |
| continuity layer | The governed layer that provides safe, non-advisory persistence for analytical workflows, modeling, and structured reuse. |
| continuity loss | A failure in which expected state is unavailable due to guardrail activation, packet rejection, or interpretation-heuristic filtering. |
| control surfaces | The governed interfaces through which supervisory rules, retention boundaries, and compliance constraints are applied to computational memory. |
| controlled substrate | The governed foundational layer beneath the model where continuity, retention, and structured reuse occur. The controlled substrate provides stable, predictable behavior across sessions while enforcing non‑advisory boundaries. |
| decision-oriented computational artifact | A prohibited packet type that implies decision‑making or directional output. |
| decision systems | Systems that generate recommendations, evaluations, or directionally suggestive outputs; computational memory must remain separate from decision logic. |
| delete operations | Governed API operations that remove retained structures under supervisory constraints to ensure no advisory state persists. |  
| deletion governance enforcement | A supervised control that ensures deletion operations follow governed rules, remain deterministic, and preserve audit visibility. |
| deletion log | A record of all deletion operations, including supervisory enforcement and audit visibility. |
| deployment sequence | The phased rollout path for installing, validating, supervising, and activating computational memory within enterprise environments. |
| directive structures | Packets that resemble instructions or guidance and are rejected at the memory boundary to prevent advisory state formation. |
| durable state | Retained, non-advisory structures that support continuity and reuse across interactions under supervised constraints. |
| enterprise controls | The governed set of checks, validations, and supervisory mechanisms required for regulated deployment of computational memory. |
| enterprise deployment pattern | The standardized model for deploying computational memory across enterprise systems, ensuring safe activation and compliance alignment. |
| enterprise-scale modeling | The ability for AI systems to support large, repeatable, multi‑session analytical workflows under governed continuity. Enterprise‑scale modeling requires stable inputs, reusable structures, and predictable behavior without forming advisory state. |
| equivalence demonstration | The formal process of showing that computational memory behaves like existing non-advisory tools and therefore qualifies for regulatory carve-out. |
| FAQ | The structured set of clarifications addressing common questions about computational memory, governance, and supervised continuity. |
| governed carve-out | The governed exemption that allows computational memory to retain non-advisory structures under supervisory controls, ensuring that persistence remains outside advisory classification while satisfying regulatory expectations. |
| governed continuity | Continuity delivered under supervisory constraints that prevent advisory state formation and ensure safe persistence. |
| governed dynamic modeling | Analytical modeling performed with continuity and reuse while remaining within non-advisory boundaries. |
| governed persistence | Retention performed under supervisory controls that ensure stored structures cannot produce advisory activity. |
| governed persistence surface | The formally constrained layer where inputs, transformations, and retained structures are persisted under supervisory controls. It provides a safe, non‑advisory perimeter for continuity operations and ensures that stored state cannot produce guidance or advisory activity. |
| governance architecture | The formal structure of supervisory controls, boundaries, and compliance mechanisms that govern computational memory. |
| guardrail activation | The triggering of regulatory controls that block advisory-risk outputs or retention events. |
| guardrail activation event | A logged event indicating that a supervised control prevented advisory state formation. |
| identity packets | Packets containing stable user identity or preference information eligible for safe retention under governed rules. |
| implementation path | The structured sequence of steps required to adopt, validate, and deploy computational memory in enterprise environments. |
| instruction-like packets | Packets that resemble directives or guidance and are rejected at the memory boundary to prevent advisory state formation. |
| interpretation heuristics | The classification logic that determines whether packets are conversational, instruction-like, advisory-risk, or eligible for safe retention. |
| long-term relevance packet | A packet type retained because it supports continuity across sessions without forming advisory state. |
| memory boundary | The governed checkpoint where packets are evaluated for eligibility, safety, and advisory-risk before retention. |
| non-advisory domain | The regulated space in which AI systems may operate without producing guidance, recommendations, or decision-shaping outputs. |
| non-directive analytical structure | A packet type that supports continuity without implying direction, suitability, or decision‑making. |
| packet classification | The process of categorizing packets into identity, preference, conversational, instruction-like, or advisory-risk classes. |
| persistence boundary | The governed limit defining what can be safely retained without forming advisory state. |
| read operations | Governed API operations that retrieve retained structures under supervisory constraints. |
| regulated boundaries | The formal constraints that prevent advisory state formation and define the safe operating perimeter for computational memory. |
| regulated guidance | Any output regulators classify as guidance, including recommendations, evaluations, or directionally suggestive conclusions. |
| regulatory carve-out | The formal exemption that allows computational memory to retain non-advisory structures without being classified as guidance. |
| regulatory gap | The structural difference between how traditional tools (such as spreadsheets) and AI systems are treated by regulators, where identical user-owned structures are permitted in tools but interpreted as advisory risk in AI, preventing continuity for AI systems. |
| retention boundary | The governed limit determining whether a packet is eligible for safe persistence. |
| retention eligibility rules | The criteria that determine whether packets qualify for retention based on identity, preference, or long-term relevance. |  
| retention eligibility gate | A supervised control that determines whether a packet type is permitted for retention. |
| safe retention | The governed process of storing non-advisory structures under supervisory constraints. |
| safe persistence layer | The governed continuity layer that retains non‑advisory structures under supervisory controls. The safe persistence layer ensures that stored state cannot produce guidance, violate regulated boundaries, or form advisory state. |
| silent failure | A continuity failure that occurs without a visible warning due to guardrail activation, packet rejection, or heuristic filtering. |
| solution | The formal path for establishing computational memory as a governed, non-advisory functional layer. |
| streamlined process | The governed implementation sequence that aligns regulators, governance teams, practitioners, and engineers on supervised continuity. The streamlined process applies supervisory controls, updates guardrails, and activates safe retention across interactions. |
| structural continuity | A packet type that preserves the structure of prior interactions without implying guidance. |
| structural failure | A systemic breakdown in continuity where users cannot maintain assumptions, models, workflows, or long-term context, even when no advice is requested, due to regulatory treatment of retained state as advisory activity. |
| structured reuse | The ability to reuse retained, non-advisory structures across interactions under governed constraints. |
| suitability-oriented structured | A prohibited packet type that implies suitability, appropriateness, or personalized direction. |
| supervised AI persistence | The governed retention of non-advisory structures under supervisory controls that prevent advisory state formation. |
| supervised continuity | Continuity delivered under supervisory constraints that ensure safe, non-advisory persistence. |
| supervised continuity layer | The governed continuity layer that explicitly separates safe persistence from advisory output, ensuring that retained structures support repeatable operation without forming advisory state or guidance. |
| supervised persistence | The governed process of retaining structures under supervisory controls that enforce non-advisory boundaries. |
| supervised retention | The controlled retention of packets under supervisory rules that prevent advisory state formation. |
| supervisory checkpoints | Governed evaluation points within the continuity layer that validate retention events, enforce compliance constraints, and prevent advisory‑risk structures from persisting. Supervisory checkpoints operate beneath the model and ensure that continuity remains within regulated boundaries. |
| supervisory controls | The governed mechanisms that enforce retention boundaries, compliance constraints, and advisory-risk prevention. |
| supervisory gates | The checkpoints that evaluate packets for advisory-risk, eligibility, and compliance before retention. |
| supervisory override | A governed mechanism allowing authorized personnel or systems to override a boundary decision under controlled conditions. |
| telemetry surface | The governed visibility layer that exposes continuity operations, supervisory actions, and retention events for audit. |
| transform operations | Governed API operations that modify retained structures under supervisory constraints. |  
| transformation boundary check | A supervised control that ensures transformations preserve non‑advisory intent and do not generate directive packets. |  
| transformation log | A record of all transformations applied to retained packets, including boundary checks and outcomes. |  
| transformation rules | The governed constraints that define how retained structures may be modified within the continuity layer. Transformation rules ensure that all modifications remain non‑advisory, compliant with regulatory boundaries, and consistent with the system’s supervised persistence model. |
| unbounded retention | A prohibited condition in which retained structures exceed governed limits, bypass supervisory controls, or create advisory‑risk state. Unbounded retention violates the persistence boundary and must be prevented by the memory boundary and supervisory gates. |
| use cases | The defined set of non-advisory continuity applications across enterprise domains. |
| white paper | The foundational document defining the AI Computational Memory Category, its governance architecture, and deployment model. |
| write operations | Governed API operations that create retained structures under supervisory constraints. |
