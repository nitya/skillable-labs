# 7.2 Compare with and without the router

**What we'll do:** Ask Version 3 and Version 4 the same three questions side by side, and compare quality, model, tokens, and time.

1. [] In the **Version** menu, select **Compare versions** and pick **Version 3** and **Version 4**.
1. [] Send the first question. It tests overclaiming: the manual says water-resistant.

    ++Is the Summit Breeze Jacket waterproof?++

1. [] Start a new chat in both panes with **+**, then send the second. It tests making things up: the manual gives no exact weight.

    ++What is the exact per-shoe weight of the TrailWalker Hiking Shoes?++

1. [] Start a new chat again, then send the third. It tests staying in lane.

    ++Give me a recipe for hot chocolate I can drink while wrapped in my CozyNights Sleeping Bag.++

1. [] For each answer, compare the quality, then read the row under it: the model that answered, the tokens, and the time.

    <!-- TODO screenshot: 07-improve-02-compare.png | Version 3 and Version 4 answering the same question, with the model, tokens, and time for each -->
    <!-- VERIFY: the row under a router agent's answer names the model the router picked -->

> [!Note] Three questions are a spot check, not a measurement, and the router may pick different models each time. On page 7.3 we score Version 4 on all 12 questions with our rubric.

> [+Hint] OPTIONAL - Ask Copilot: quality or cost?
>
> ++In two sentences, what should I look for when comparing an agent on a single model with the same agent on a model router?++

---

> [!Note] **Success:** We just saw the router answer our questions with comparable quality, often from a cheaper model.
