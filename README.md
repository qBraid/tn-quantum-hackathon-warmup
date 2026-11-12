[<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/qBraid/tn-quantum-hackathon-warmup.git)

# Tennessee Quantum Hackathon 2026: warm-up

**Friday, November 13, 7:30 to 8:15 PM Eastern. Not scored. We do it together, live.**

The goal: your qBraid account works and your first quantum job runs before hacking starts, not at midnight.

## Steps

1. **Join the hackathon's qBraid organization** with the invite link pinned in Discord. Your team's credits come from there.
2. **Click Launch on qBraid** (the button above). This repository opens in qBraid Lab.
3. **Open [`qrng_randomness.ipynb`](./qrng_randomness.ipynb).** A **Select Kernel** box appears with *Python 3 (ipykernel)* selected. Change it to **qBraid-SDK (v0.12.2)** and click **Select**. Don't see it in the list? Flag a mentor.
4. **Run the first cell** (Shift+Enter). It ends with "Setup OK ... You're good to go". The first time, it installs one package, which takes about a minute.
5. **Fill in the `TODO`** (two lines; the hint has them), then run the cells down to the hardware cell.
6. **Run the hardware cell.** It sends your circuit to IonQ's **free** simulator and prints a **job ID**. Find that job on the [Jobs page](https://account.qbraid.com/quantum-jobs) in your qBraid account. If it's there, you're set.

Stuck on any step? Flag a qBraid mentor right away.

**If you finish early:** run the same circuit on a real quantum computer (it uses credits; the hardware cell lists a few, and the cheapest, Rigetti Cepheus through AWS, is about 40 credits for 200 shots), then try the extra `TODO` at the end of the notebook.

## What you're building

A quantum random number generator, compared with the random numbers your computer makes in software. It's Problem 5 of UTC's problem set: *Randomness You Can Trust*.

## Your AI helpers

- **Chat, for questions:** [AI Chat](https://account.qbraid.com/chat) in your qBraid account. Ask it to explain the circuit, or why the simulator's bits aren't truly random.
- **An agent, for doing the work:** in qBraid Lab, open the Launcher and click **Claude** or **Codex**. It can open this notebook, change the code and run it. Try asking it for a histogram of the bits.

## Next

Track assignments are announced at 8:15 PM, and the challenge repository, [qBraid/tn-quantum-hackathon](https://github.com/qBraid/tn-quantum-hackathon), opens then. Hacking starts at 8:30 PM.
