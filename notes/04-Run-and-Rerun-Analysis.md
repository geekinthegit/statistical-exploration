## 01. Rare Category Analysis

### Target Utterance and Category Boundary

| Item | Description |
|---|---|
| source_id | 75963 |
| Target utterance | “Did you want to add something” |
| Human label | Getting Students to Relate |
| Label 1 | Keeping Everyone Together |
| Label 2 | Getting Students to Relate |
| Preceding context | The teacher praises Student A and his team before producing the target utterance. |
| Next teacher utterance | “Comment awesome” |
| Subsequent student response | “I agree with your answer but I did it differently on how to figure it out” |
| Basis for label 1 | The target utterance can be read as a general invitation to take a speaking turn. |
| Basis for label 2 | The student agrees with another student’s answer and contrasts their solution methods. This response relates directly to another student’s contribution. |
| Boundary ambiguity | The target utterance does not explicitly identify what the student is invited to add to. Managing turns and inviting a response to another student’s ideas may overlap. |

### Replicate-Level Results Across Runs

**1 = Keeping Everyone Together; 2 = Getting Students to Relate.**

Replicate labels are listed in the order **Replicate 1 → Replicate 2 → Replicate 3**. The final label is determined by majority vote.

| Condition | Original run: replicate labels | Original run: final label | Rerun: replicate labels | Rerun: final label | Final-label change |
|---|---|---|---|---|---|
| Baseline | 2 → 1 → 1 | 1 | 1 → 1 → 1 | 1 | Unchanged |
| Definitions replaced | 1 → 1 → 1 | 1 | 2 → 2 → 2 | 2 | **1 → 2** |
| Examples replaced | 1 → 1 → 1 | 1 | 1 → 1 → 1 | 1 | Unchanged |
| Exclusion rules replaced | 2 → 2 → 2 | 2 | 2 → 2 → 2 | 2 | Unchanged |
| Negative control | 1 → 1 → 2 | 1 | 1 → 1 → 1 | 1 | Unchanged |
| Names-only | 1 → 1 → 1 | 1 | 1 → 1 → 1 | 1 | Unchanged |

### Agreement with the Human Label

| Run | Conditions whose final label matched the human label |
|---|---|
| Original run | Exclusion rules replaced |
| Rerun | Definitions replaced; Exclusion rules replaced |

### Notable Observations and Interpretations

| Point | Observation | Interpretation |
|---|---|---|
| Within-run consistency differs from between-run consistency | The definitions-replaced condition produced 1·1·1 in the original run and 2·2·2 in the rerun. | Unanimous responses within each run did not ensure the same final label across runs. |
| Agreement under exclusion-rule replacement was observed again | The exclusion-rules-replaced condition produced 2·2·2 in both runs. | All six observed responses matched the human label for this item. This does not establish that future responses would always do so. |
| Unchanged final labels can conceal replicate-level variation | Baseline and the negative control each produced label 2 once in the original run, but only label 1 in the rerun. | Comparing final labels alone would miss these differences. |
| Exclusion-rule replacement was not the only condition yielding a matching final label | In the rerun, the definitions-replaced condition also had final label 2. | Agreement with the human label cannot be described as occurring exclusively under exclusion-rule replacement across both runs. |
| Boundary ambiguity and output variation occurred in the same case | The utterance permits overlapping functional interpretations, and labels differed across conditions and runs. | Ambiguity may be related to the variation, but a causal relationship has not been established. |
| Item-level agreement must be distinguished from the overall effect | For this item, exclusion-rule replacement yielded greater agreement with the human label than Baseline in both runs. | This does not establish that exclusion rules are unnecessary or harmful across the full sample. |

**Scope of interpretation:** This is a descriptive comparison of one utterance across two runs. Interpreting the differences as variation under identical conditions requires the prompts, context, model snapshot, and invocation settings to have remained unchanged. The labels alone do not reveal which rules or contextual cues the model relied on.