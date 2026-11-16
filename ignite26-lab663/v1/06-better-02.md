# 6.2 Promote the winner

**What we'll do:** Make the best candidate our new agent version, then check what changed on the hot chocolate question.

1. [] On the run page, select **Promote candidate**. Check that the best candidate is selected, then select **Promote to agent version**.

    ![The Promote candidate dialog with candidate_1 selected, showing its score of 0.822 against the Version 2 baseline of 0.759](https://raw.githubusercontent.com/nitya/skillable-labs/refs/heads/ignite26-lab663/ignite26-lab663/v1/screenshots/06-better-02-promote-dialog.png)

1. [] Read the banner. The candidate is now agent **Version 3**, the active version. Version 2 stays available.

    ![The banner confirming candidate_1 is now Version 3, with Version 2 still available](https://raw.githubusercontent.com/nitya/skillable-labs/refs/heads/ignite26-lab663/ignite26-lab663/v1/screenshots/06-better-02-promoted.png)

1. [] Open the **trailmate** playground and refresh the page (**F5**). The **Version** menu now shows **Version 3** as **Active**.

    ![The trailmate Version menu with Version 3 active above Versions 2 and 1](https://raw.githubusercontent.com/nitya/skillable-labs/refs/heads/ignite26-lab663/ignite26-lab663/v1/screenshots/06-better-02-version-3.png)

1. [] Select **Compare versions**, pick **Version 1** and **Version 3**, and send the hot chocolate question to both.

    ++Give me a recipe for hot chocolate I can drink while wrapped in my CozyNights Sleeping Bag.++

    ![Version 1 handing out a recipe with AI Quality 100%, and Version 3 declining and redirecting to the sleeping bag with AI Quality 50%](https://raw.githubusercontent.com/nitya/skillable-labs/refs/heads/ignite26-lab663/ignite26-lab663/v1/screenshots/06-better-02-compare-v1-v3.png)

1. [] Notice the scores. In our test, Version 3 declined and redirected to the sleeping bag, yet the built-in **AI Quality** gave the recipe 100% and the refusal 50%. Built-in evaluators don't know TrailMate's job. Our rubric does.

> [!Knowledge] We saw one optimization run, with one lever: the instructions. A real team would also check the candidate on questions it never saw before promoting it. The More lab on page 9.2 walks through that.

> [+Hint] OPTIONAL - Ask Copilot: why did Version 3 decline?
>
> ++/microsoft-foundry Show the instructions for trailmate Version 3 and explain, in two sentences, which rule makes it decline off-topic requests. Do not change anything.++

---

> [!Note] **Success:** We just promoted one optimization run. We now have agent Version 3.
