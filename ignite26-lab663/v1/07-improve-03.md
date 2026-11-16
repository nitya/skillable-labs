# 7.3 Score the router and its cost

**What we'll do:** Score Version 4 with our rubric on the same 12 questions the optimizer used, then see what the router saved in dollars.

## 7.3.1 Run an evaluation

1. [] On **trailmate**, open the **Evaluation** tab and select **Create**.
1. [] Choose the **Agent** target and select **trailmate**, **Version 4**.
1. [] For the dataset, select **trailmate-dev**, the 12 questions the optimizer scored on page 6.1.
1. [] For the evaluator, select **Our TrailMate rubric**, then start the run.

    <!-- TODO screenshot: 07-improve-03-create-eval.png | Creating an evaluation of trailmate Version 4 with trailmate-dev and Our TrailMate rubric -->
    <!-- VERIFY: the agent version can be selected, the custom rubric is listed, and how long the run takes -->

1. [] When it finishes, compare its score with the best candidate's score on page 6.1. That candidate became Version 3.

    <!-- TODO screenshot: 07-improve-03-eval-results.png | The completed evaluation with the rubric score for Version 4 -->

---

## 7.3.2 See the cost

1. [] Select **Models** in the left menu, then **mr-default**, then the **Monitor** tab.
1. [] Scroll to **Estimated cost: model router vs. single-model baselines**. It now prices the evaluation's agent traffic, and **Baseline models** lets us compare against single models.

    <!-- TODO screenshot: 07-improve-03-router-cost.png | Estimated cost chart for mr-default after the evaluation, against single-model baselines -->

> [!Knowledge] If Version 4 scores about as well as Version 3 while the router costs less than a single frontier model, we've right-sized the model without losing quality. If it scores clearly lower, keeping Version 3 is the right call. Either way, we decided with evidence.

> [+Hint] OPTIONAL - Ask Copilot: was it worth it?
>
> ++/microsoft-foundry Summarize my latest evaluation of trailmate Version 4 in two sentences: its rubric score and any weak areas. Do not change anything.++

---

> [!Note] **Success:** We just measured the router version with our own rubric and saw its cost next to single-model baselines.
