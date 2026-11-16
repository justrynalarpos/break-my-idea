# Break My Idea

A ChatGPT skill for testing an idea before you build it. It picks the assumption most likely to change your next decision and gives you a cheap experiment to test it.

## What it does

- Identifies one assumption that matters to the idea.
- Designs one experiment and defines what would count as a promising, weak, or inconclusive result.
- Gives you a first step and helps you interpret the results when you bring them back.

## How to use it

1. Open [SKILL.md](SKILL.md). If you have the Skills tab in ChatGPT, follow the [OpenAI skills guide](https://help.openai.com/en/articles/20001066-skills-in-chatgpt) to add it. You can also paste the Markdown into a chat.
2. Ask ChatGPT to break your idea. Include who it helps and any time or budget constraints.

## Example

> Break my idea for a browser extension that alerts resellers when a listing drops in price.

**Assumption** — Active resellers will pay $10 a month for faster, relevant alerts.

**Test** — Recruit five resellers who already check listings. Ask which items they track, manually send them relevant alerts for a week, then offer to keep sending alerts for $10 a month. Count paid signups among the five participants.

**Decision** — If all five received relevant alerts and saw the offer, two or more paid signups justify a larger trial. Zero or one is a weak result for this offer. If the alerts were irrelevant or some participants missed the offer, treat the result as inconclusive. The price and cutoff are illustrative.

**First step** — Find five resellers willing to try the manual version.
