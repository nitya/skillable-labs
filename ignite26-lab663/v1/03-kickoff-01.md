# 3.1 Create v1 and leave traces

**What we'll do:** Change one lever, the instructions, to create TrailMate **v1**, then ask it 12 practice questions so it leaves traces for Foundry to analyze. The optimizer on the next page learns from these.

1. [] In the Explorer, open **labs > core > 04-make-it-work.ipynb**.
1. [] Select the **.venv (3.13.14)** kernel, the same way as on page 1.3.
1. [] In the **Outline**, click **4.8 What does Foundry think is wrong?**, then click the first code cell below that heading.
1. [] Hover over that cell and click the **Execute Above Cells** icon in its toolbar. This runs sections 4.1 to 4.7 in order and stops before 4.8.

    ![The first section 4.8 code cell with the Execute Above Cells icon highlighted in its toolbar](https://raw.githubusercontent.com/nitya/skillable-labs/refs/heads/ignite26-lab663/ignite26-lab663/v1/screenshots/03-kickoff-01-execute-above.png)

1. [] Use the Outline to follow along. The first cell prints **Connected. 12 practice questions ready.**, and section **4.4** prints **Saved. TrailMate v1 is Foundry version 2**.

    > [!Note] This is the moment **trailmate** moves to agent **Version 2** in Foundry. From here on, the portal opens trailmate at Version 2, our climb version **v1**. Version 1, our baseline **v0**, is still there in the **Version** menu.

    ![The first cell printing Connected. 12 practice questions ready.](https://raw.githubusercontent.com/nitya/skillable-labs/refs/heads/ignite26-lab663/ignite26-lab663/v1/screenshots/03-kickoff-01-connected.png)

1. [] Wait for section **4.7** to count down. It pauses one minute so the traces can arrive. The whole run takes a couple of minutes.

    ![Section 4.7 counting down Waiting for traces](https://raw.githubusercontent.com/nitya/skillable-labs/refs/heads/ignite26-lab663/ignite26-lab663/v1/screenshots/03-kickoff-01-waiting.png)

1. [] While it waits, switch to the Foundry portal. Expand the left menu with its toggle at the bottom left, then select **Traces**. The 12 practice conversations appear one by one, each with its duration and tokens.

    ![The Foundry Traces list filling with trailmate traces, with duration and tokens](https://raw.githubusercontent.com/nitya/skillable-labs/refs/heads/ignite26-lab663/ignite26-lab663/v1/screenshots/03-kickoff-01-portal-traces.png)

> [+Hint] Ask Copilot: what just ran?
>
> ++Summarize what sections 4.1 to 4.7 of labs/core/04-make-it-work.ipynb did, in three bullets. Don't change any files.++

---

> [!Note] **Success:** We just finished **Make it work** (notebook 04): TrailMate v1 is created, and Foundry has 12 conversations' worth of traces to learn from.
