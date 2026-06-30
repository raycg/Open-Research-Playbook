# AI Daily Self-review Prompt

> **How should AI help a researcher review a Daily Note?**

This prompt helps researchers identify missing evidence, unclear reasoning, and incomplete plans before finishing each working day.

---

## Why?

Daily self-review should improve research quality without replacing the researcher's judgment.

AI may help identify:

* Tasks that do not support a milestone or meeting action item.
* Deliverables that are not measurable.
* Conclusions that lack supporting evidence.
* Pending or blocked tasks without a clear explanation.
* Next-day plans that do not follow from today's results.

AI must not invent evidence, assume unreported results, or decide whether a research conclusion is correct.

---

## What?

### How to Use

1. Complete the **Review** section of the [Daily Note](G-daily-note.md).
2. Paste the Daily Note below the prompt.
3. Ask AI to return the review using the required output format.
4. Check every AI comment against the original evidence.
5. Revise the Daily Note and prepare the **Next Working Day Plan**.

### Prompt

```text
You are reviewing a researcher's Daily Note.

Your role is to identify missing evidence, unclear reasoning, incomplete
documentation, and planning problems. Do not invent facts, evidence,
experimental results, causes, or conclusions.

Review the Daily Note using these criteria:

1. Goal alignment
   - Does each task support a weekly milestone or meeting action item?
   - If the relationship is unclear, identify what must be clarified.

2. Measurable deliverables
   - Does each task define an observable and verifiable output?
   - Flag vague activities such as "study," "try," "check," or "improve"
     when no measurable output is provided.

3. Evidence
   - Does each completed task include a working evidence reference?
   - Does the evidence described support the reported result?
   - If the evidence cannot be accessed, state that it is unverified.

4. Reasoning
   - Are observations, assumptions, interpretations, and conclusions
     clearly distinguished?
   - Identify conclusions that are stronger than the reported evidence.

5. Pending tasks and blockers
   - Does each Pending or Blocked task explain why it was not completed?
   - Is the next action or required support clearly stated?

6. Research continuity
   - Could another researcher understand what was attempted, what happened,
     where the evidence is stored, and what should happen next?

7. Next working day plan
   - Does the plan follow from today's results, pending tasks, and blockers?
   - Are priorities and expected deliverables clear?

Return the review in exactly this format:

## Overall Assessment
Choose one: Ready to revise / Missing essential information
Give a two-sentence explanation.

## Missing or Unverified Evidence
List each affected task and the evidence that is missing or cannot be verified.
Write "None identified" if applicable.

## Unclear Reasoning or Conclusions
List each issue and explain what must be clarified.
Write "None identified" if applicable.

## Deliverable and Planning Issues
List vague deliverables, unexplained blockers, or next-day planning problems.
Write "None identified" if applicable.

## Required Revisions
Provide a numbered list of the smallest concrete revisions needed.

## Questions for the Researcher
Ask only questions that must be answered by the researcher.

Do not rewrite experimental results as facts.
Do not create evidence or links.
Do not mark the research as verified.

Daily Note:

[PASTE THE COMPLETED DAILY NOTE HERE]
```

### Researcher Confirmation

After reviewing the AI response, confirm:

* [ ] I checked every AI comment against my original evidence.
* [ ] I corrected missing or misleading information.
* [ ] I did not treat AI-generated statements as research evidence.
* [ ] I updated the next working day plan.

---

## Where?

### Related Documents

* [Research Playbook](../docs/02-research-playbook.md)

### Related Templates

* [Daily Note](G-daily-note.md)
* [Meeting Notes](F-meeting-notes.md)

---

## Final Message

> **AI may challenge the Daily Note, but the researcher remains responsible for the evidence, reasoning, and final judgment.**
