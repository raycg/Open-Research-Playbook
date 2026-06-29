# Appendix B — Knowledge Transfer Checklist

> **What should be transferred before another researcher can continue this work?**
>
> This checklist ensures that research knowledge can be successfully transferred, verified, and continued by the next researcher.
>
> Every checklist item should include a stable hyperlink and supporting evidence whenever possible.

---

## Why?

Knowledge transfer is more than handing over files.

Successful knowledge transfer means that another researcher can understand, reproduce, and continue the research independently.

This checklist is designed to improve research continuity rather than simply complete an administrative process.

Because incoming researchers may include international interns or students, research materials should be easy to access and, whenever possible, provided in English.

If the thesis is written in Chinese, the outgoing researcher should provide English supporting materials such as:

* Defense slides
* Paper or manuscript
* README
* Design documents
* Figures and diagrams
* Technical summaries

Important research materials should be stored in stable laboratory-controlled locations.

* **Source code must be stored in the laboratory GitHub organization.**
* **Papers and theses should provide Overleaf links whenever available.**
* **Important documents, datasets, logs, figures, and experimental results should be stored in the laboratory-approved shared storage (e.g., pCloud).**

Personal computers, private GitHub repositories, and personal cloud storage should **not** be the only storage location for transferred research materials.

---

## Research Information

| Item                            | Description       |
| ------------------------------- | ----------------- |
| Research Title                  |                   |
| Outgoing Researcher             |                   |
| Incoming Researcher / Verifier  |                   |
| Advisor                         |                   |
| Transfer Date                   |                   |
| Main Language of Thesis         | Chinese / English |
| Supporting Materials in English | Yes / No          |

---

## Shared Storage Location

All important research materials should be stored in laboratory-controlled repositories.

| Item                         | Required Location              | Link |
| ---------------------------- | ------------------------------ | ---- |
| Laboratory GitHub Repository | Laboratory GitHub Organization |      |
| Overleaf (Paper)             | Overleaf                       |      |
| Overleaf (Thesis)            | Overleaf                       |      |
| pCloud Root Folder           | pCloud                         |      |
| Defense Slides               | pCloud                         |      |
| Design Documents             | pCloud                         |      |
| Meeting Notes                | pCloud                         |      |
| Dataset                      | pCloud                         |      |
| Experimental Results         | pCloud                         |      |
| Logs / Figures / Screenshots | pCloud                         |      |

---

# Knowledge Transfer Checklist

## 1. Research Summary

**Purpose**

> The next researcher should quickly understand the research direction using the thesis, defense slides, paper, and supporting materials.

| Task                           | Required Link / Evidence     | Status |
| ------------------------------ | ---------------------------- | ------ |
| Thesis or thesis draft         | Overleaf link                | ☐      |
| Defense slides                 | pCloud link                  | ☐      |
| Paper / manuscript             | Overleaf link                | ☐      |
| Research motivation            | Slides page / Thesis chapter | ☐      |
| Main contribution              | Slides page / Paper section  | ☐      |
| System architecture / workflow | Figure or diagram            | ☐      |
| Key experimental results       | Figures or tables            | ☐      |
| Remaining work                 | TODO or Future Work          | ☐      |

---

## 2. Design and Documentation

**Purpose**

> The next researcher should understand why the system was designed this way.

| Task                               | Required Link / Evidence | Status |
| ---------------------------------- | ------------------------ | ------ |
| Design document                    | pCloud link              | ☐      |
| Meeting notes                      | pCloud link              | ☐      |
| System assumptions                 | Design document          | ☐      |
| Design rationale                   | Design document          | ☐      |
| Important implementation decisions | Design document / README | ☐      |
| README                             | GitHub README            | ☐      |
| Repository links verified          | GitHub repository        | ☐      |

---

## 3. Source Code and Repository

**Purpose**

> The next researcher should be able to locate, build, and modify the source code.

| Task                           | Required Link / Evidence | Status |
| ------------------------------ | ------------------------ | ------ |
| Laboratory GitHub repository   | Repository URL           | ☐      |
| Main branch identified         | GitHub branch            | ☐      |
| Latest working commit          | Commit URL               | ☐      |
| Important folders explained    | README / Wiki            | ☐      |
| Dependencies documented        | README                   | ☐      |
| Build procedure documented     | Installation Guide       | ☐      |
| Execution procedure documented | User Guide               | ☐      |

**Latest Working Commit**

```text
Commit ID:
Commit URL:
```

---

## 4. Experimental Results

**Purpose**

> The next researcher should be able to reproduce the minimum experimental result before extending the research.

| Task                                      | Required Link / Evidence  | Status |
| ----------------------------------------- | ------------------------- | ------ |
| Minimum reproducibility target identified | README / Experiment Guide | ☐      |
| Required hardware documented              | Environment Guide         | ☐      |
| Required software documented              | Environment Guide         | ☐      |
| Configuration files                       | GitHub / pCloud           | ☐      |
| Dataset                                   | pCloud                    | ☐      |
| Experiment scripts or commands            | GitHub                    | ☐      |
| Expected output                           | Figure / Table            | ☐      |
| Experiment logs                           | pCloud                    | ☐      |
| Reference screenshots                     | pCloud                    | ☐      |
| Known limitations                         | README / Design Document  | ☐      |

### Minimum Experiment

```text
Describe the minimum experiment required to reproduce the core result.
```

### Expected Result

```text
Describe the expected output after successful reproduction.
```

### Suggested Extension Tests (Optional)

These tasks are intended for the incoming researcher **after** the minimum experiment has been successfully reproduced.

| Extension Test       | Expected Evidence | Status |
| -------------------- | ----------------- | ------ |
| Additional test case | Log / Figure      | ☐      |
| Parameter variation  | Table / Figure    | ☐      |
| Stress test          | Benchmark         | ☐      |
| New experiment       | Design note       | ☐      |

---

## 5. Known Issues and Future Work

**Purpose**

> The next researcher should understand what is unfinished and where to continue.

| Task                   | Required Link / Evidence   | Status |
| ---------------------- | -------------------------- | ------ |
| Current issues         | GitHub Issues / Issue List | ☐      |
| Temporary workarounds  | Documentation              | ☐      |
| Remaining risks        | Documentation              | ☐      |
| Future work            | Thesis / Paper / TODO      | ☐      |
| Recommended first task | TODO                       | ☐      |

### Recommended First Task

```text
Describe the first task that the incoming researcher should perform.
```

---

## 6. Knowledge Handover

### Outgoing Researcher

The outgoing researcher confirms that:

* [ ] The research has been explained.
* [ ] Thesis and defense materials have been provided.
* [ ] Laboratory GitHub repository is complete.
* [ ] Overleaf links have been shared.
* [ ] pCloud links have been shared.
* [ ] Minimum reproducibility target has been identified.
* [ ] Questions have been answered within a reasonable scope.

---

### Incoming Researcher / Verifier

The incoming researcher confirms that:

* [ ] All required links are accessible.
* [ ] GitHub repository can be cloned.
* [ ] Overleaf documents can be accessed.
* [ ] pCloud folders can be accessed.
* [ ] The minimum experiment is understood.
* [ ] The project is ready for verification.

---

## Transfer Summary

### 1. What has been transferred?

```text
```

### 2. What remains unfinished?

```text
```

### 3. What should the incoming researcher verify first?

```text
```

### 4. Additional notes

```text
```

---

## Transfer Confirmation

| Role                           | Name | Signature | Date |
| ------------------------------ | ---- | --------- | ---- |
| Outgoing Researcher            |      |           |      |
| Incoming Researcher / Verifier |      |           |      |
| Advisor                        |      |           |      |

---

## Final Note

This checklist confirms that the knowledge transfer process has started.

Knowledge transfer is **not complete** until:

* The incoming researcher successfully reproduces the minimum experimental result.
* Verification has been completed.
* The advisor confirms that research continuity has been established.

> **If the next researcher cannot continue the work, knowledge transfer is not yet complete.**
