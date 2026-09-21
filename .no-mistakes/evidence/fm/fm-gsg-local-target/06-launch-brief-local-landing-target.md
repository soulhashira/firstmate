# Task
## Captain's intent
Land verified GSG work on the chosen local simulation branch.

## Firstmate spec
Exercise the local landing target selection.

# Definition of done
Delivery contract: mode=local-only

# Current worker role contract
When this task works on Firstmate itself, this section supersedes every earlier brief instruction about your role and identity.
When this task works on Firstmate itself, the repository root `AGENTS.md` (also imported by `CLAUDE.md`) is the primary/secondmate supervisor's contract: follow this brief instead of that supervisor contract.
For that Firstmate task, do the assigned work yourself and report to firstmate; do not adopt the supervisor identity, delegate the task, run fleet supervision, or address the captain.
This exception preserves this brief's safety and authority boundaries and applicable contributor guidance, including `CONTRIBUTING.md` and `firstmate-coding-guidelines` for Firstmate changes.
Other projects retain their own instructions unchanged.

# Current local landing target
This section supersedes every earlier brief instruction about which branch your `fm/gsg-t1` branch must stay a fast-forward of.
This task lands on local branch `gsg-sim`, checked out in `/tmp/fm-live-spawn.WHX9lK/selected/target`.
Rebase `fm/gsg-t1` onto `gsg-sim` whenever that branch advances, so the eventual landing stays a clean fast-forward.
Never check out, commit to, or otherwise write in `/tmp/fm-live-spawn.WHX9lK/selected/target`; firstmate performs the guarded landing there after the configured merge authority approves.
