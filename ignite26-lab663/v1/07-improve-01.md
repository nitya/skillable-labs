# 7.1 Try a model router

**What we'll do:** Keep v2's instructions and change only the model, to the **mr-default** router. Then score it with the same rubric and questions.

1. [] In the Explorer, open **labs > core > 06-make-it-optimal.ipynb**.
1. [] Select the **.venv (3.13.14)** kernel, the same way as on page 1.3.

1. [] In the first code cell, leave `RUN_ALL_EDITIONS = False` and `TOLERANCE` as they are, then run it.
1. [] Run section **6.2** and note how many test questions are tagged easy.
1. [] Run section **6.3** and compare the models it shows with what you saw in the playground on pages 4.3 and 4.4. It mentions a hand-built router from Module 3. That's an optional More lab (page 9.1), so skip that line.
1. [] Run section **6.4** to create the router candidate, then section **6.5** to score it. Scoring takes a few minutes.

    > [+Hint] While you wait: all four router editions
    >
    > We score only mr-default today. Here's a completed run with all four editions side by side.
    >
    > <!-- TODO screenshot: 07-improve-01-all-editions.png | A completed board comparing the baseline with all four router editions -->

1. [] Confirm the board has a baseline row and an **mr-default** row. If `valid` is False, that batch can't support a comparison.

    <!-- TODO screenshot: 07-improve-01-board.png | The section 6.5 board with the baseline and mr-default rows -->

> [+Hint] Ask Copilot: summarize the router board
>
> ++Summarize the board in section 6.5 of labs/core/06-make-it-optimal.ipynb in three bullets: quality, cost, and errors. Don't change any files.++

---

> [!Note] **Success:** We just measured a router candidate with the same ruler as every earlier version.
