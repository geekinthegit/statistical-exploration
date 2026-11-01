## 01. Rare Category Analysis

**Source ID:** 75963  
**Human label:** Getting Students to Relate (2)

### Context

```text
T: Hand signals one and onefourth
T: Awesome
T: Sorry our board has just been acting up lately
T: One and onefourth
T: Awesome
T: Three claps for [Student A] and his team
T: Awesome job friends
[TARGET] T: Did you want to add something
T: Comment awesome
S: I agree with your answer but I did it differently on how to figure it out
T: You want to tell us
S: Yes
S: I took the five and put it over  and then I  how many times four goes into five
S: One and then there is onefourth added on to it
T: Thats great math thinking
```

### Results

1 = Keeping Everyone Together; 2 = Getting Students to Relate.

| Condition | Run (1 → 2 → 3) | Final label | Rerun (1 → 2 → 3) | Final label |
|---|---|---|---|---|
| Baseline | 2 → 1 → 1 | 1 | 1 → 1 → 1 | 1 |
| Definitions replaced | 1 → 1 → 1 | 1 | 2 → 2 → 2 | 2 |
| Examples replaced | 1 → 1 → 1 | 1 | 1 → 1 → 1 | 1 |
| Exclusion rules replaced | 2 → 2 → 2 | 2 | 2 → 2 → 2 | 2 |
| Negative control | 1 → 1 → 2 | 1 | 1 → 1 → 1 | 1 |
| Names-only | 1 → 1 → 1 | 1 | 1 → 1 → 1 | 1 |

## 02. Bootstrap Distributions

Point estimates and 95% bootstrap confidence intervals from 10,000 resamples.

| Condition | Original run | Rerun | Overlay |
|---|---|---|---|
| Baseline (κ) | ![Run](../images/bootstrap-run-rerun-graphs/01-original-run/01-baseline.png) | ![Rerun](../images/bootstrap-run-rerun-graphs/02-rerun/01-baseline.png) | ![Overlay](../images/bootstrap-run-rerun-graphs/03-overlay/01-baseline.png) |
| Definitions replaced (Δκ) | ![Run](../images/bootstrap-run-rerun-graphs/01-original-run/02-definitions.png) | ![Rerun](../images/bootstrap-run-rerun-graphs/02-rerun/02-definitions.png) | ![Overlay](../images/bootstrap-run-rerun-graphs/03-overlay/02-definitions.png) |
| Examples replaced (Δκ) | ![Run](../images/bootstrap-run-rerun-graphs/01-original-run/03-examples.png) | ![Rerun](../images/bootstrap-run-rerun-graphs/02-rerun/03-examples.png) | ![Overlay](../images/bootstrap-run-rerun-graphs/03-overlay/03-examples.png) |
| Exclusion rules replaced (Δκ) | ![Run](../images/bootstrap-run-rerun-graphs/01-original-run/04-exclusion-rules.png) | ![Rerun](../images/bootstrap-run-rerun-graphs/02-rerun/04-exclusion-rules.png) | ![Overlay](../images/bootstrap-run-rerun-graphs/03-overlay/04-exclusion-rules.png) |
| Negative control (Δκ) | ![Run](../images/bootstrap-run-rerun-graphs/01-original-run/05-negative-control.png) | ![Rerun](../images/bootstrap-run-rerun-graphs/02-rerun/05-negative-control.png) | ![Overlay](../images/bootstrap-run-rerun-graphs/03-overlay/05-negative-control.png) |