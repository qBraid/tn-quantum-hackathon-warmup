[<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/qBraid/tn-quantum-hackathon-warmup.git)

# Tennessee Quantum Hackathon 2026: warm-up

**Friday, November 13, 7:30 to 8:15 PM Eastern. Not scored. We do it together, live.**

The point is to get your qBraid account and a first quantum job working now, not at midnight.

## First: join the hackathon's qBraid organization

Use the invite link pinned in Discord. That's where your team's credits come from.

## The warm-up

1. **Open this repository in qBraid Lab** with the **Launch on qBraid** button above.
2. **Open [`qrng_randomness.ipynb`](./qrng_randomness.ipynb)** and pick the qBraid SDK environment's kernel (Kernel > Change Kernel). The first cell installs qiskit-aer if it's missing, and stops with a message if you're on the wrong kernel.
3. **Fill in the first `TODO`** (two lines) and run every cell down to the hardware cell.
4. **Run the hardware cell as written.** It sends your circuit to IonQ's **free** simulator on qBraid and prints a **job ID**. If qBraid prints a warning about measurements, that's expected. Don't switch to a real quantum computer tonight: save your credits and queue time for your track.
5. **Open the [Jobs page](https://account.qbraid.com/quantum-jobs)** in your qBraid account and find that job. If it's there, your account works.

Stuck on any step? Flag a qBraid mentor right away.

## What you're building

**Randomness You Can Trust:** a quantum random number generator, compared with the randomness your computer makes in software. It comes from UTC's problem set. The second `TODO`, after the hardware cell, is extra if you finish early.

## Set up your AI helpers

Now's a good time to try the AI helpers you'll use this weekend:

- **Chat, for questions.** [AI Chat](https://account.qbraid.com/chat) is built into your qBraid account. Try asking it to explain the QRNG circuit, or why the simulator's bits aren't truly random.
- **An agent, for doing the work.** In qBraid Lab, open the Launcher and click the **Claude** or **Codex** icon. The agent runs inside your Lab, so it can open this notebook, change the code and run it. Try asking it to add a histogram of the QRNG bits.

## After the warm-up

Track assignments are announced at 8:15 PM. The challenge repository, [qBraid/tn-quantum-hackathon](https://github.com/qBraid/tn-quantum-hackathon), opens then, with your problem set and starter notebooks. Hacking starts at 8:30 PM.
