# Research Playbook

> **How do we conduct research every working day?**

This document defines the daily research workflow of the Open Research Playbook.

---

## Why?

Research activities should produce measurable results and reproducible evidence.

Every working day should help researchers:

* Understand the problem before taking action.
* Verify conclusions with evidence.
* Preserve essential research knowledge.
* Enable another researcher to continue the work.

---

## What?

### Research Lifecycle

| Lifecycle | Daily Practice | Output |
|---|---|---|
| 🧠 Think | Prepare the morning plan in the [Daily Note](../templates/G-daily-note.md) | Daily Plan |
| 🔬 Verify | Complete the evening review and use the [AI Daily Self-review Prompt](../templates/E-ai-daily-self-review-prompt.md) | Verified Daily Report |
| 📝 Document | Record decisions and evidence in [Meeting Notes](../templates/F-meeting-notes.md) | Reproducible Knowledge |
| 🤝 Transfer | Follow the [Knowledge Transfer Workflow](10-knowledge-transfer.md) | Research Continuity |

```mermaid
flowchart TD
    M["Meeting Notes<br/>Action Items"]
    P["Daily Note<br/>Morning Plan"]
    R["Research Work"]
    V["Daily Note<br/>Evening Review"]
    A["AI Daily Self-review"]
    N["Next Working Day Plan"]

    M --> P
    P --> R
    R --> V
    V --> A
    A --> N
    N --> P
    N --> M
