## Project Timeline
**Total duration: 7–10 working days**

**Breakdown:**

* **Day 1–2:**
  Deep analysis of provided completed examples (reverse-engineering tone, intent, structure, constraints, output variance).
* **Day 3–6:**
  Design & build production-grade prompts:

  * Content planning systems
  * Caption generation systems
  * Onboarding & strategy document systems
* **Day 7–8:**
  Stress-testing prompts for:

  * First-run accuracy
  * Consistent formatting
  * Edge-case handling
* **Day 9–10 (if needed):**
  Final refinements + documentation (usage instructions, variables, guardrails).

**Goal:** The Goal is **zero dependency on follow-ups** — prompts must work correctly on first execution.


## Approach to First-Pass Prompt Accuracy

I don’t write prompts as “instructions”. I design them as **controlled generation systems**.

### My methodology:

### 1. Reverse-Engineering First

I deconstruct client examples into:

* Output schema (headings, slide logic, sequencing)
* Linguistic patterns (authority markers, persuasion triggers)
* Tone constraints (confidence level, vocabulary ceiling)
* Variance bounds (what can change vs what must not)

This ensures **replication, not approximation**.

### 2. System-Level Prompt Architecture

Each prompt includes:

* **Explicit role enforcement** (non-negotiable behavior)
* **Hard output schema** (formatting the model cannot break)
* **Intent locks** (why content exists, not just what it says)
* **Negative constraints** (what the model must avoid)
* **Deterministic sequencing** (slide-by-slide or section-by-section logic)

No open-ended creativity unless explicitly required.
### 3. Variance Control

Prompts are engineered with:

* Fixed content logic
* Controlled stylistic variation
* Predictable length & density

So output feels **human and fresh**, but never structurally unstable.

### 4. First-Run Stress Testing

I test prompts across:

* Different avatars
* Weak vs strong inputs
* Minimal vs detailed briefs

If a prompt needs a “small tweak” after testing → **it doesn’t ship**.


## Examples of GPT Assistants & Testable Output

Due to NDAs, I can’t publicly share client links.
However, I can **immediately provide testable samples**.

### Example: Carousel Content Planning Prompt (Authority – Fitness Coach)

**Input (what client provides):**

```
Avatar: Online fitness coach for busy professionals  
Goal: Position as authority without hype  
Platform: Instagram  
Offer: 12-week body recomposition program
```

**First-Run Output (excerpt):**

```
Carousel Theme: “Why Most Busy Professionals Never Get Lean”

Slide 1 (Hook):
You’re not failing at fitness.
You’re following a system designed for people with time you don’t have.

Slide 2 (Reframe):
Busy professionals don’t need more workouts.
They need fewer decisions.

Slide 3 (Authority Insight):
After coaching 100+ clients with 50–60 hr workweeks,
the problem is never motivation — it’s misaligned structure.

Slide 4 (Belief Shift):
Consistency isn’t about discipline.
It’s about friction removal.

Slide 5 (Framework):
The 3 constraints that actually matter:
• Time compression
• Recovery debt
• Cognitive load

Slide 6 (Soft Proof):
Every client who fixed these saw visible changes in 4–6 weeks.

Slide 7 (CTA):
If your schedule is full, your system shouldn’t be.
```

**Note:** This output is **structured, publish-ready, and requires zero editing**.

I can share **live prompts** for you to test before final approval.


## Pricing: 

Pricing is **per production-ready prompt**, not per word.

### Prompt Rates:

* **Content Planning Prompts (Carousel / Authority / B-roll):**
  **PKR 15,000 – 20,000 per prompt**

* **Caption Writing Prompts (Authority / Credibility / Carousel):**
  **PKR 12,000 – 18,000 per prompt**

* **Onboarding & Strategy Document Prompts (Avatar, Offer, Team):**
  **PKR 20,000 – 30,000 per prompt**

### Bundle Option (Recommended):

Full reusable prompt library (10–12 prompts):
👉 **PKR 150,000 – 180,000**

Includes:

* Usage instructions
* Input variables
* Output guarantees
* Prompt versioning for reuse



## Final Note (Must Read)

This is **not creative prompting**.
This is **production system design** for GPT assistants that:

* Work on first run
* Maintain quality at scale
* Can be reused across clients without degradation

If needed, I can deliver **one paid test prompt first** before full engagement.
