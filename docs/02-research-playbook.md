## What?

### Research Lifecycle

| Lifecycle | Daily Practice | Output |
|-----------|----------------|--------|
| 🧠 Think | [Daily Note](../templates/G-daily-note.md) (Morning Plan) | Daily Plan |
| 🔬 Verify | [Daily Note](../templates/G-daily-note.md) (Evening Report) + [AI Daily Self-review Prompt](../templates/E-ai-daily-self-review-prompt.md) | Daily Report |
| 📝 Document | [Meeting Notes](../templates/F-meeting-notes.md) | Reproducible Knowledge |
| 🤝 Transfer | [Knowledge Transfer](10-knowledge-transfer.md) | Research Continuity |

```mermaid
graph TD
    MN[Meeting Notes<br/>New Action Items]
    DN1[Daily Note<br/>Morning Plan]
    R[Research Work]
    DN2[Daily Note<br/>Review]
    AI[AI Daily Self-review]
    NP[Next Working Day Plan]
    NM[Next Meeting<br/>Review Pending Tasks]

    MN --> DN1
    DN1 --> R
    R --> DN2
    DN2 --> AI
    AI --> NP
    NP --> DN1
    NP --> NM
    NM --> MN
```    
---

### 🧠 Think

Prepare a **[Daily Note](../templates/G-daily-note.md)** before starting work.

---

### 🔬 Verify

Complete the **Evening Report** in the **[Daily Note](../templates/G-daily-note.md)**.

Review it using the **[AI Daily Self-review Prompt](../templates/E-ai-daily-self-review-prompt.md)**.

---

### 📝 Document

Record research knowledge using the **[Meeting Notes](../templates/F-meeting-notes.md)**.

---

### 🤝 Transfer

Prepare research knowledge following the **[Knowledge Transfer](10-knowledge-transfer.md)** workflow.
