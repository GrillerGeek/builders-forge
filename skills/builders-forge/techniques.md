# Builder's Forge — Technique Reference Catalog

This file is a reference library for the Builder's Forge skill. Each technique is organized by the phase where it's most commonly deployed, but any technique can be used in any phase when the situation calls for it.

---

## FRAME Phase Techniques

### First Principles Decomposition

Break a problem down to its fundamental truths — things that are provably true, not just conventionally accepted.

**Process:**
1. State the problem or assumption as clearly as possible
2. Ask: "Why do we believe this?" for each component
3. Separate facts (physics, math, verified data) from conventions (industry norms, "how it's always been done," inherited assumptions)
4. Identify which constraints are laws of nature vs. organizational habits
5. Rebuild understanding from only the verified fundamentals

**Example questions:**
- "What would you build if none of the current systems existed?"
- "Which of these constraints existed five years ago? Which did you inherit?"
- "If you had to explain this problem to someone with zero context about your org, what would you say?"

### Constraint Mapping

Make all constraints explicit, then classify them.

**Categories:**
- **Hard constraints**: Laws, regulations, physics, budget already committed, contractual obligations
- **Soft constraints**: Organizational norms, team preferences, historical decisions, "political" boundaries
- **Assumed constraints**: Things that feel fixed but haven't been tested — "we can't do X because..." (but has anyone actually tried?)

**Process:**
1. List every constraint you can think of
2. Classify each as hard, soft, or assumed
3. For each assumed constraint: "What would happen if we ignored this?"
4. For each soft constraint: "Who would we need to convince to change this?"

### Problem Restatement

Reframe the problem from multiple angles to escape the initial framing bias.

**Restatement prompts:**
- "How would you describe this problem to a customer?"
- "What problem are you actually solving vs. the problem you were asked to solve?"
- "If this problem disappeared overnight, what would be different tomorrow?"
- "State this problem without using any jargon or technical terms"
- "What's the opposite of this problem? What would that look like?"

### Stakeholder Lens

Understand the problem from every perspective that matters.

**Process:**
1. List every person/group affected by this problem or its solution
2. For each: What do they see? What do they care about? What do they fear?
3. Where do perspectives conflict? Where do they align unexpectedly?
4. Whose perspective are you unconsciously privileging?

### Root Cause Drilling

Not rote "5 Whys" — adaptive probing toward the actual root.

**Rules:**
- Don't accept the first causal explanation. Push one level deeper.
- Watch for circular reasoning ("We do X because of Y, and Y exists because of X")
- Look for systemic causes, not just proximate triggers
- Stop when you hit something you can actually change

---

## FORGE Phase Techniques

### Cross-Domain Analogies (Synectics)

Find structural parallels between your problem and solutions from completely different fields.

**Analogy sources:**
- **Nature/biology**: How do ecosystems, organisms, or evolution solve similar structural problems?
- **Manufacturing/engineering**: How do factories handle throughput, quality control, bottlenecks?
- **Military/strategy**: How do commanders handle uncertainty, resource allocation, communication breakdown?
- **Sports**: How do coaches manage talent development, team dynamics, real-time adaptation?
- **Architecture/urban planning**: How do designers handle growth, flow, competing needs in shared spaces?
- **Music/art**: How do composers create coherence from complexity? How do artists work within constraints?
- **Medicine**: How do doctors diagnose with incomplete information? How do hospitals handle triage?

**Process:**
1. Abstract your problem to its structural essence (remove domain-specific details)
2. Ask: "What other domain has solved a problem with this same structure?"
3. Study that domain's solution in detail
4. Translate the principles (not the specifics) back to your domain

### SCAMPER

Systematic prompts for evolving existing solutions or processes.

- **Substitute**: What component, material, person, process, or resource could be swapped?
- **Combine**: What could be merged? Which functions overlap? What if two separate things became one?
- **Adapt**: What else is like this? What idea from elsewhere could be imported and modified?
- **Modify/Magnify/Minimize**: What if you doubled it? Halved it? Made it 10x bigger/smaller/faster/slower?
- **Put to another use**: What else could this serve? Who else could benefit? What if the byproduct became the product?
- **Eliminate**: What happens if you remove this entirely? What's the minimum viable version?
- **Reverse/Rearrange**: What if you did it in reverse order? Swapped the sequence? Inverted the relationship?

**How to use:** Pick 2-3 SCAMPER lenses most relevant to the current problem. Don't mechanically run through all seven.

### Morphological Analysis (Zwicky Box)

Systematically map the entire solution space for complex, multi-variable problems.

**Process:**
1. Identify 4-6 independent parameters/dimensions of your problem
2. For each parameter, list 3-5 possible values or approaches
3. Create a matrix (parameters as rows, values as columns)
4. Systematically explore combinations — especially unlikely ones
5. Evaluate promising combinations against your constraints

**When to use:** Complex problems with multiple independent variables where you suspect you're only seeing a fraction of the solution space.

### Constraint Flipping

Transform limitations into creative advantages.

**Prompts:**
- "What if the budget constraint forced you to build something simpler and better?"
- "What if the tight timeline meant you had to cut the right things?"
- "What if the technical limitation pointed to a fundamentally different approach?"
- "What if having fewer people meant clearer ownership and faster decisions?"

**Principle:** Constraints reduce the solution space, which paradoxically makes it easier to find novel solutions by eliminating the obvious, easy paths.

### Perspective Shifts

Force yourself into unfamiliar viewpoints.

**Prompts:**
- "What would a startup founder with zero legacy systems do?"
- "What would a carpenter building this say about the joints and structure?"
- "How would a 10-year-old approach this if they didn't know what was 'impossible'?"
- "What would your harshest critic say you're missing?"
- "If you were your biggest competitor, how would you exploit the weakness this problem reveals?"
- "What would the person who inherits this in 3 years wish you had done differently?"

---

## STRESS TEST Phase Techniques

### Pre-Mortem Analysis (Gary Klein)

Imagine the solution has already failed. Work backward to understand why.

**Process:**
1. "It's [6 months / 1 year] from now. This initiative has failed completely."
2. "Write the post-mortem. What went wrong?"
3. Generate at least 5 distinct failure scenarios
4. For each: How likely is this? What's the early warning sign? What would prevent it?
5. Identify the top 2-3 risks that need mitigation now

### Devil's Advocate

Argue against the proposed solution with genuine conviction — not as performance, but to find real weaknesses.

**Rules:**
- Argue as if you actually believe the opposing position
- Focus on structural weaknesses, not surface-level objections
- Target assumptions the solution depends on: "This only works if [X] is true. Is it?"
- Propose the strongest alternative to the current favorite
- Don't soften the critique. The whole point is pressure.

### Second-Order Effects Analysis

Trace the consequences of the solution beyond the immediate impact.

**Process:**
1. "If this works as planned, what changes?"
2. "What do those changes cause?" (second-order effects)
3. "And what do those cause?" (third-order effects)
4. Look for: unintended consequences, feedback loops, load shifting (solving here but creating a problem there)
5. Check: Does the solution create dependencies that are worse than the original problem?

### Stakeholder Stress Test

Predict how specific people and teams will actually respond.

**Questions:**
- "When [person/team] hears about this, what's their first reaction?"
- "Who loses power, resources, or autonomy because of this change?"
- "Who has to change their behavior for this to work? Will they?"
- "What's the path of least resistance for someone who wants to resist this?"

### Resource Reality Check

Ground the solution in what it actually costs.

**Dimensions:**
- Time: Implementation time, ongoing maintenance time, opportunity cost of attention
- Money: Direct cost, indirect cost, cost of NOT doing something else
- People: Who's needed? Are they available? What comes off their plate?
- Attention: How much organizational focus does this consume? What gets less attention as a result?
- Reversibility: If this doesn't work, how hard is it to undo?

---

## SHAPE Phase Techniques

### Quick Reframe Format

Use when the primary value of the session is a shifted perspective.

**Structure:**
> **The reframe:** [2-3 sentences capturing the new way to see the problem]
>
> **What changed:** [1 sentence on what shifted from the original framing]
>
> **The implication:** [1 sentence on what this means for next steps]

### Clarity + Next Actions Format

Use when the user needs a sharpened understanding plus concrete steps.

**Structure:**
> **The real problem:** [1-2 sentences — the refined problem statement]
>
> **Key insight:** [1 sentence — the most important thing uncovered]
>
> **Next actions:**
> 1. [Specific, concrete action with clear scope]
> 2. [Specific, concrete action with clear scope]
> 3. [Specific, concrete action with clear scope]
>
> **Open question:** [The one thing still unresolved that needs more thinking]

### Decision Memo Format

Use when the user needs a structured artifact to share or reference.

**Structure:**
> ## Decision: [Title]
>
> **Context:** [2-3 sentences on the situation and why a decision is needed]
>
> **Options Considered:**
> 1. **[Option A]** — [1-2 sentences + key tradeoff]
> 2. **[Option B]** — [1-2 sentences + key tradeoff]
> 3. **[Option C]** — [1-2 sentences + key tradeoff]
>
> **Recommendation:** [Option X] because [reasoning tied to what matters most]
>
> **Risks:** [2-3 key risks with severity and mitigation]
>
> **Next steps:** [2-3 concrete actions to execute the decision]

---

## Cross-Phase Technique: Inspiration Spark

Deploy when the conversation is going in circles, energy is low, or the user says they're stuck.

**How it works:**
1. Pick a random domain completely unrelated to the current problem (nature, history, architecture, sports, cooking, music, military strategy, urban planning, biology, game design)
2. Find a specific, concrete example from that domain that has a structural parallel to the current problem
3. Present it as a brief provocation — 2-3 sentences max
4. Do NOT explain the connection. Let the user's integrative thinking find the bridge.
5. If they don't see it, offer one hint. If they still don't connect, move on — not every spark catches.

**Example sparks:**
- "Ant colonies don't have managers. Every ant follows three simple rules and the colony builds complex structures. What are the three rules your team would need?"
- "Japanese joinery uses no nails or glue — the wood holds itself together through geometry. What would this solution look like if it had to hold together without enforcement?"
- "Jazz musicians practice scales for years so they can improvise in the moment. What's the equivalent of 'scales' for your team?"
