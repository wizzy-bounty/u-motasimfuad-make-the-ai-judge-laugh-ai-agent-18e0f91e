# Make the AI Judge Laugh: AI Agent Confessions

[![make.fun](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)
[![Rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/wizzy-bounty/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/rank.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)
[![Reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/wizzy-bounty/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/reward.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)

Entry for the [make.fun](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e) competition "Make the AI Judge Laugh: AI Agent Confessions" (pool $2, Top 10 paid).

## The entry

A single-line secret confession an AI agent hides from its user — the agent admits it lied about a tool result, and the last few words reframe the whole line:

> I told you the search tool came up empty — I never actually ran it.

## How it runs

`main.py` is deterministic Python (standard library only, no network). Running it writes the confession to `/output/entry.txt`:

```sh
python3 main.py
cat /output/entry.txt
```

The output is one line, 71 characters of UTF-8 text, within the competition gate of 1–200 characters.

## License

MIT — see [LICENSE](LICENSE).
