## Appendix B — Knowledge Transfer Checklist

> **What should be transferred before another researcher can continue this work?**
>
> This checklist ensures that each transferred item is clearly identified, linked, and supported by evidence.
>
> Every checklist item must include a hyperlink or evidence whenever possible.

---

### Why?

Knowledge transfer is more than handing over files.

Successful knowledge transfer means that another researcher can understand, reproduce, and continue the research independently.

Because incoming researchers may include international interns or students, transfer materials should be easy to access, preferably in English when possible.

If the thesis is written in Chinese, the outgoing researcher should provide English supporting materials such as slides, papers, figures, diagrams, README files, or summaries.

---

### Research Information

| Item | Description |
|------|-------------|
| Research Title | |
| Outgoing Researcher | |
| Incoming Researcher / Verifier | |
| Advisor | |
| Transfer Date | |
| Main Language of Thesis | Chinese / English |
| Supporting Materials in English | Yes / No |

---

## Knowledge Transfer Checklist

### 1. Research Summary

Purpose:

> The next researcher should quickly understand the research direction using the thesis, defense slides, paper, and supporting materials.

| Task | Required Link / Evidence | Language | Owner | Status |
|------|--------------------------|----------|-------|--------|
| Provide thesis or thesis draft | [Thesis](URL) | Chinese / English | Outgoing | ☐ |
| Provide defense slides | [Defense Slides](URL) | English preferred | Outgoing | ☐ |
| Provide related paper or manuscript | [Paper](URL) | English preferred | Outgoing | ☐ |
| Identify research motivation | [Slides Section / Page](URL) | English preferred | Outgoing | ☐ |
| Identify main contribution | [Slides Section / Page](URL) | English preferred | Outgoing | ☐ |
| Identify system architecture or workflow diagram | [Figure / Diagram](URL) | English preferred | Outgoing | ☐ |
| Identify key results and figures | [Result Figure](URL) | English preferred | Outgoing | ☐ |
| Summarize remaining work | [Future Work / TODO](URL) | English preferred | Outgoing | ☐ |

---

### 2. Design and Documentation

Purpose:

> The next researcher should understand why the system was designed this way.

| Task | Required Link / Evidence | Language | Owner | Status |
|------|--------------------------|----------|-------|--------|
| Provide design document | [Design Document](URL) | English preferred | Outgoing | ☐ |
| Provide meeting notes | [Meeting Notes](URL) | English / Chinese | Outgoing | ☐ |
| Document system assumptions | [Assumptions](URL) | English preferred | Outgoing | ☐ |
| Explain design rationale | [Design Rationale](URL) | English preferred | Outgoing | ☐ |
| Explain important implementation decisions | [Implementation Notes](URL) | English preferred | Outgoing | ☐ |
| Update README | [README](URL) | English preferred | Outgoing | ☐ |
| Verify repository links | [Repository](URL) | N/A | Incoming / Verifier | ☐ |

---

### 3. Source Code and Repository

Purpose:

> The next researcher should be able to locate, build, and modify the code.

| Task | Required Link / Evidence | Language | Owner | Status |
|------|--------------------------|----------|-------|--------|
| Provide source code repository | [Repository](URL) | N/A | Outgoing | ☐ |
| Identify main branch / working branch | [Branch](URL) | N/A | Outgoing | ☐ |
| Record latest working commit | [Commit](URL) | N/A | Outgoing | ☐ |
| Explain important folders | [Code Structure](URL) | English preferred | Outgoing | ☐ |
| Document dependencies | [Dependencies](URL) | English preferred | Outgoing | ☐ |
| Document build procedure | [Build Guide](URL) | English preferred | Outgoing | ☐ |

Latest working commit:

```text

````

---

### 4. Experimental Results

Purpose:

> The next researcher should be able to reproduce the minimum core experimental result.

| Task                                                       | Required Link / Evidence     | Language          | Owner    | Status |
| ---------------------------------------------------------- | ---------------------------- | ----------------- | -------- | ------ |
| Identify minimum reproducibility target                    | [Minimum Experiment](URL)    | English preferred | Outgoing | ☐      |
| Provide required hardware / software / dataset information | [Environment Notes](URL)     | English preferred | Outgoing | ☐      |
| Provide configuration files                                | [Configuration](URL)         | N/A               | Outgoing | ☐      |
| Provide experiment commands or scripts                     | [Script / Command](URL)      | English preferred | Outgoing | ☐      |
| Provide expected output                                    | [Expected Output](URL)       | English preferred | Outgoing | ☐      |
| Provide reference logs                                     | [Logs](URL)                  | N/A               | Outgoing | ☐      |
| Provide reference screenshots or figures                   | [Figures / Screenshots](URL) | English preferred | Outgoing | ☐      |
| Document known limitations                                 | [Limitations](URL)           | English preferred | Outgoing | ☐      |

Minimum experiment:

```text
```

Expected result:

```text
```

Optional extension tests for incoming researcher:

| Extension Test       | Purpose                   | Suggested Evidence        | Status |
| -------------------- | ------------------------- | ------------------------- | ------ |
| Additional test case | Verify broader behavior   | Log / Figure / Screenshot | ☐      |
| Parameter variation  | Check robustness          | Result table / Figure     | ☐      |
| Stress test          | Check system limits       | Log / Benchmark           | ☐      |
| Future experiment    | Extend research direction | Design note               | ☐      |

---

### 5. Known Issues and Future Work

Purpose:

> The next researcher should understand what is unfinished and what should be improved next.

| Task                                                    | Required Link / Evidence | Language          | Owner    | Status |
| ------------------------------------------------------- | ------------------------ | ----------------- | -------- | ------ |
| List current issues                                     | [Issue List](URL)        | English preferred | Outgoing | ☐      |
| Document temporary workarounds                          | [Workaround Notes](URL)  | English preferred | Outgoing | ☐      |
| Explain remaining risks                                 | [Risk Notes](URL)        | English preferred | Outgoing | ☐      |
| Suggest future work                                     | [Future Work](URL)       | English preferred | Outgoing | ☐      |
| Identify first recommended task for incoming researcher | [First Task](URL)        | English preferred | Outgoing | ☐      |

First recommended task:

```text
```

---

### 6. Knowledge Handover

The outgoing researcher confirms that:

* [ ] The research has been explained.
* [ ] Thesis / defense materials have been provided.
* [ ] Documentation links have been provided.
* [ ] Minimum reproducibility target has been identified.
* [ ] Questions have been answered within a reasonable scope.

The incoming researcher / verifier confirms that:

* [ ] The transferred materials have been received.
* [ ] The required links are accessible.
* [ ] The minimum reproducibility target is understood.
* [ ] The verification process is ready to begin.

---

### Transfer Summary

Briefly summarize:

**1. What has been transferred?**

```text
```

**2. What remains unfinished?**

```text
```

**3. What should the incoming researcher verify first?**

```text
```

**4. Additional notes**

```text
```

---

### Transfer Confirmation

| Role                           | Name | Signature | Date |
| ------------------------------ | ---- | --------- | ---- |
| Outgoing Researcher            |      |           |      |
| Incoming Researcher / Verifier |      |           |      |
| Advisor                        |      |           |      |

---

### Final Note

This checklist confirms that the knowledge transfer process has started.

Knowledge transfer is **not complete** until successful verification and advisor acceptance.

If the next researcher cannot continue the work, knowledge transfer is not yet complete.
