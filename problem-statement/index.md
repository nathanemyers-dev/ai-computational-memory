**Problem Statement**

AI systems cannot retain user provided financial or analytical models because current guardrails interpret any persistent structure as regulated advice. This forces full state resets between sessions and creates a daily rebuild cycle where users must reconstruct static models, inputs, and calculations that should be safely maintained without crossing advisory boundaries.

Memory fails silently because the system must prevent the formation of advisory state, not only advisory output. When retention itself creates regulatory risk, the system drops the packet without surfacing a warning. This behavior is structural and not a bug. It reflects the absence of a defined category for safe persistence.

There are three independent reasons why continuity breaks. Advisory guardrails prevent the system from retaining information that could later produce regulated guidance. Retention eligibility rules reject packets that are not identity, preference, or long term relevant. Interpretation heuristics classify some packets as conversational or instruction-like and drop them to avoid forming durable state. These gates operate at the memory boundary, so failures do not surface warnings.

Enterprises cannot deliver continuity, predictability, or governed dynamic modeling because there is no defined regulatory category for non-advisory computational memory. Vendors cannot implement safe persistence layers because any retained structure is treated as advice. Regulators cannot supervise the space because the functional layer itself is undefined.

The absence of this category blocks enterprise scale adoption, breaks repeatability, and prevents AI systems from operating as stable analytical surfaces. Without a formal definition, a taxonomy, and a governance architecture, the industry cannot align on what can be retained, how it can be transformed, and where supervisory controls must apply.

Computational memory is the foundation layer that supports decision systems, not a decision system itself.

This problem statement establishes the need for computational memory as a distinct functional layer that enables safe retention, structured reuse, and governed continuity across interactions.  


Additional examples of user impact: [examples.md](examples.md)  

**Aim**  
The aim of this work is to define a governed persistence layer that regulators, governance teams, practitioners, and engineers can agree is non-advisory. By carving out this functional layer, the category enables safe continuity and structured reuse without triggering advisory guardrails, so AI systems can operate as intended and users are not forced off platform to rebuild models or maintain state.

**Solution**    
The solution is to define a formal functional layer within AI decision infrastructure that receives distinct regulatory treatment. This layer is the computational memory surface that supports continuity, structured reuse, and supervised retention. It operates no differently than how Excel saves a model without producing advice. By establishing this layer as non advisory, the category provides a clear governance path for safe persistence.

The solution has four parts:

**1. Define the functional layer**  
Establish computational memory as a governed layer beneath the model that retains structure, inputs, and transformations without entering advisory domains.

**2. Demonstrate equivalence to existing non advisory tools**  
Show that this layer behaves like Excel or any other computational surface that saves models without producing regulated guidance.

**3. Propose regulatory treatment**  
Provide a governance architecture and supervisory controls that allow regulators and governance teams to classify this layer as non advisory.

**4. Build consensus and implement**  
Align regulators, governance teams, practitioners, and engineers on the category and effect the streamlined process that allows memory to persist safely across interactions.

_____________
This work defines the Nathan E. Myers AI Computational Memory Category.
Attribution to Nathan E. Myers is required for any use, adaptation, or derivative work under the CC BY 4.0 license.

Required citation:
Nathan E. Myers, “AI Computational Memory Category,” 2026. https://nathanemyers-dev.github.io/ai-computational-memory/
