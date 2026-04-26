# Thesis Notes

## My Notes
<!-- notes, thoughts, ideas go here -->
- 2.2, how are different architectures used differently, which is used as buy/sell and which is used in portfolio management, and how?
- Stock price forecasting, integrate qualitative information-how/focus on time-series forecasting with LLMs, how/why?
- Sentiment analysis, lexical scoring to agent-based approaches, what?
- Automated trading and decision systems, autonomous trading systems, what? integrate sentiment analysis for trading and portfolio management/incorporate reinforcement learning, sorry?
- enhance model interpretability, how?
- traditional optimisation methods to reinforcement learning, more pls.
- addressed the reliability of LLMs in equity markets, how?
- Reinforcement Fine-Tuning, outline the difference between rl-driven and rft.
- 2.3, tie all this back to your approach, outline the paper categorization as investment research/alpha-mining/rl-driven, tie back to fine-tuning papers that show
enhancement, tie back to rl-driven that show enhancement, tie back to alpha-mining concept, and more importantly to rlhf and rlmf, mention lora adapters and peft.
- Methodology, add more math, more on grpo, mention other algorithms, why grpo? deepseek did what? how?
- System overview, summarize and explain approach and tie back to related work, and algorithm.
- what is trading strategy? what is output?
- what is backtesting? more on reward function. say something in the end?

---

## To-Do
- Rewrite research gap
- Refactor contributions
- Include reference for RNN and LSTM
- Include references for healthcare [60], education [61]
- Include reference for chatgpt if possible
- shown in ?? 4.1
- Rewrite thesis outline (last)
- Rewrite as paper


### Writing
- [ ] Write the **Abstract**
- [ ] Fill in Chapter 5 (Experiments) — datasets, hardware, baselines, evaluation metrics
- [ ] Fill in Chapter 5 Results section with actual numbers
- [ ] Fill in Chapter 5 Analysis / ablation studies
- [ ] Write Chapter 6 (Conclusion) — Summary, Limitations, Future Work

### Citations — Missing `\cite{}` keys
These are placeholders in the text that need real references added to `references.bib`:

| Placeholder | Where used | What's needed |
|---|---|---|
| `TODO-healthcare` | §2.3 LLMs intro | LLM in healthcare paper |
| `TODO-education` | §2.3 LLMs intro | LLM in education paper |
| `TODO-survey84` | §2.3.1 LLM in equity markets | Survey of 84 LLM-finance papers |
| `TODO-llm-trading-survey` | §2.3.2 LLMs in trading | Survey that defines LLM-as-trader vs alpha-miner |
| `TODO-llm-trader-refs` | §2.3.2 | Papers where LLMs directly generate buy/hold/sell |
| `TODO-alpha-factor` | §2.3.2 | Alpha factor / alpha miner paper |
| `TODO-alpha-miner-refs` | §2.3.2 | Papers where LLMs generate alpha factors |
| `TODO-openai-rft` | §2.3.3 RFT | OpenAI reinforcement fine-tuning paper/post |
| `TODO-unsloth` | §3.2 System Overview | Unsloth library citation |
| `TODO-backtrader` | §3.2 Back-testing | Backtrader citation |

### References — Incomplete `.bib` entries
All existing entries in `references.bib` are missing `journal`, `volume`, `pages`, `doi`. These need completing before submission.

Also, many `\cite{}` keys used in the text (e.g. `bajpai2021`, `brim2022`, `carta2021`, `shi2024`, `ni2024`, etc.) have no corresponding entry in `references.bib` at all — need to be added.

### Misc
- [ ] Replace "in this **paper**" with "in this **thesis**" throughout (currently appears in §1.4 and §2 intro)
- [ ] Remove `\listoffigures` / `\listoftables` from front matter if Chapters 4–5 don't add more figures/tables (currently only 2 figures and 2 tables)
- [ ] Placeholder dataset table in §4.1 (Dataset A/B) needs real data

---

## Ideas / Future Work Notes
<!-- Ideas for the thesis, experiments to try, future directions -->



---

## Supervisor Feedback
<!-- Log feedback from Prof. Ashour & Prof. El Badawy with dates -->



---

## Reading List
<!-- Papers to read, summarise, or cite -->


