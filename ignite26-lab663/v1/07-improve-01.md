# 7.1 Switch to the model router

**What we'll do:** Keep Version 3's instructions and change one lever, the model, to the **mr-default** router. Saving it creates agent **Version 4**.

1. [] In the **trailmate** playground, check that **Version 3** is selected.
1. [] Open the **Model** menu and change **gpt-5.4** to **mr-default**.

    <!-- TODO screenshot: 07-improve-01-model-menu.png | The trailmate Model menu with mr-default selected on Version 3 -->

1. [] Select **Save**. Foundry saves the change as a new agent version.
1. [] Open the **Version** menu. **Version 4**, the router version, is now **Active**, above Version 3.

    <!-- TODO screenshot: 07-improve-01-version-4.png | The trailmate Version menu with Version 4 active above Version 3 -->
    <!-- VERIFY: Save creates Version 4 rather than overwriting Version 3 -->

> [!Knowledge] Versions 3 and 4 have the same instructions and tools. Only the model differs, so any change in quality, cost, or latency comes from the router.

> [+Hint] OPTIONAL - Ask Copilot: router in an agent?
>
> ++How does a Microsoft Foundry agent behave when its model is a model router deployment? Explain in two sentences.++

---

> [!Note] **Success:** We just created agent Version 4: the optimized instructions, now on the model router.
