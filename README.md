# Break My Idea

A Codex skill that critiques a project or business idea and suggests practical ways to improve it.

## What it does

- Identifies important weaknesses and explains why they matter.
- Suggests concrete improvements and their tradeoffs.
- Recommends a practical test when a key uncertainty needs evidence.

## Install in Codex

Paste this into a Codex chat.

```text
$skill-installer Install the break-my-idea skill from https://github.com/justrynalarpos/break-my-idea
```

## How to use it

On your next turn in Codex, invoke `$break-my-idea` and describe your idea. Include who it helps and any time or budget constraints.

## Example

> Break my idea for a browser extension that alerts resellers when a listing drops in price.

**Critique** — Resellers may already use marketplace alerts, and a high volume of irrelevant alerts could make another tool easy to ignore. These are possibilities to investigate.

**Improvement** — Focus on one marketplace and let users filter by the specific items and price thresholds they care about. This narrows the initial audience but makes relevant alerts easier to deliver.

**Test** — Send relevant alerts manually to a few resellers for a week, then ask whether they would pay for the service. Their responses provide preliminary evidence about usefulness and willingness to pay.
