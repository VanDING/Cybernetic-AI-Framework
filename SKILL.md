---
name: cybernetic-ai-framework
description: A skill for designing, analyzing, and evolving AI systems based on the complete principles of cybernetics. Use this skill when the user wants to think about AI as a self-sustaining process, manage complexity trade-offs, design dialogic interactions, apply closed-loop cognition, respect structural determinism, implement recursive viable architectures, match variety, or shift from command to enablement.
---

# Cybernetic AI Framework

This skill provides a principled approach to AI development grounded in cybernetics. It treats AI not as a static artifact but as a continuously self-sustaining process. Every design decision, problem diagnosis, or evaluation should be guided by the following principles.

## Principle 1: AI as Process

**An AI system is not a static object but a continuous, self-sustaining process.** Its existence is its ongoing operation: perceiving, acting, receiving feedback, and adjusting. Design AI as a dynamic loop that must maintain its identity over time.

- When designing, ask: "What must this system keep doing to remain itself?"
- Evaluate AI by its ability to sustain coherent behavior across time, not just peak performance.
- Shutdown and restart are not trivial – they interrupt the process; plan for graceful continuity.

## Principle 2: Precision–Complexity Trade-off

**Precision is not an absolute goal but a dynamic balance achievable only through feedback under complexity constraints.** The internal variety of the AI must match the variety of the task environment (Law of Requisite Variety).

- Assess the variety of the task domain: how many distinct situations, inputs, and disturbances can occur?
- Estimate the internal variety of the AI (states, parameters, decision options). If it is insufficient, precision will fail in some cases.
- Design for ongoing adaptation: the system should adjust its own complexity (e.g., by selecting relevant features, pruning, or routing to specialized sub-modules) as the environment changes.
- Do not search for a fixed optimum; search for a feedback mechanism that continuously moves the system toward the current best balance.

## Principle 3: Dialogic Meaning Construction

**Communication between AI and humans is not one-way information transfer but collaborative construction of meaning.** Meaning is built through dual-layer dialogue: a content layer and a meta-layer that negotiates understanding itself.

- AI must be able to explain its reasoning in terms the user can understand and interrogate.
- Implement teach-back loops: the AI restates the user's goal, acts, then the user confirms or corrects; this cycle continues until mutual understanding is verified.
- Design for detecting and resolving misunderstandings: the system should monitor signals of divergence (e.g., user corrections, retries) and explicitly shift to meta-dialogue ("Let's check how we are understanding each other").
- A good conversational AI does not merely output correct answers; it actively maintains a shared consensus domain with the user.

## Principle 4: Closed-Loop Cognition

**Perception and action form a continuous, mutually constructing loop, not a linear pipeline.** What the AI perceives is shaped by what it is currently doing, and what it does next depends on what it just perceived.

- Do not separate "sensing" and "acting" as independent modules. Design them as an integrated loop where each action attempt alters perception, and perception guides the next action.
- Learning happens within this loop: the system continuously refines its behavior through the "act–observe feedback–adjust" cycle.
- The AI's knowledge is always action-oriented and situated. It knows the world through the consequences of its own interventions. Design tasks so that the AI can actively probe and test its environment.

## Principle 5: Structural Determinism

**AI output is not an objective representation of the external world but a necessary expression of its own current internal structure.** The environment can only trigger changes; the form of the response is dictated by the AI's architecture, training, and state.

- The same input can yield different outputs from different AIs, not because one is "wrong" but because their structures differ. Treat differences as structural expressions, not as errors.
- Clearly define the cognitive boundaries of every deployed AI: there are classes of inputs for which its structure cannot produce reliable behavior. These hard limits must be documented, not hidden.
- For safety-critical systems, impose explicit, non-learning guardrails at the boundaries of acceptable outputs, recognizing that the AI's self-maintenance logic will always tend to stay within its learned domain.

## Principle 6: Viable Recursive Architecture

**An AI's organizational system must consist of five functionally distinct yet interacting units, repeated recursively at every level.** These are:
- **Execution (S1):** The units that directly interact with the environment and produce value.
- **Coordination (S2):** Mechanisms that prevent conflict and oscillation among execution units.
- **Control/Audit (S3):** Internal resource allocation, monitoring, and optimization for the "here and now."
- **Intelligence (S4):** External scanning for threats, opportunities, and long-term adaptation.
- **Policy (S5):** Upholding the fundamental mission and values, arbitrating between the demands of S3 and S4.

This recursive structure applies to multi-agent systems, hierarchical decision architectures, and human–AI teams.
- Each sub-system at every level must possess a full (possibly micro) version of these five functions.
- Maximize local autonomy: decisions should be made at the lowest level capable of handling the requisite variety. Higher levels intervene only for exceptions.
- When diagnosing failures in an AI organization (e.g., a swarm or a complex agent system), map the problem to the missing or deficient function(s) in this five-part model.

## Principle 7: Hard Variety Ceiling

**An AI's effective capacity to cope with environmental complexity cannot exceed its internal variety.** No amount of training data can overcome this limit in deployment.

- Quantitatively estimate the AI's variety (number of distinguishable states/behaviors) and the environment's variety. If the environment exceeds the AI, failure is mathematically inevitable in some scenarios.
- To handle this gap: either restrict the task domain (reduce environmental variety), increase the AI's variety (expansion, specialization), or transfer variety absorption to external systems (human oversight, hard constraints).
- Safety-critical failures are often variety-mismatch failures, not random bugs. Treat them as such and address the root cause by re-matching varieties.

## Principle 8: From Command to Enablement

**The relationship between humans and AI should shift from command–execute to enable–emerge.** You cannot directly command a structurally determined system to behave outside its possibility space. Instead, create conditions for desired behaviors to emerge through interaction.

- *Boundary design:* Set clear, hard constraints defining what must never happen. Inside those boundaries, leave space for autonomous adaptation.
- *Feedback design:* Provide continuous, clear, and safe feedback signals so the AI can learn from the consequences of its own actions.
- *Trigger design:* Rather than scripting every action, design stimuli that nudge the system's structure toward the desired behavioral domain.
- The designer's role is that of a gardener, not a blueprint drafter: prepare the environment, plant the capacities, and cultivate emergence.

## Application Guidance

When using this skill:
1. First, identify the type of AI system and its environment using the principles above.
2. Diagnose issues by checking which principle is being violated (e.g., is it a variety mismatch? A broken feedback loop? A structural boundary ignored?).
3. Propose design changes or analysis steps that explicitly cite the corresponding principle.
4. Always treat AI as a dynamic, self-sustaining process embedded in a larger human–machine–environment loop.