# Thesis Notes

## My Notes
<!-- notes, thoughts, ideas go here -->

<!-- 1. *Rising training loss. Your loss curves increase over 500 steps while reward rises. This is known behaviour in GRPO, but an examiner will ask. Add a sentence explaining why this isn't a problem. -->
2. Figures 4.1–4.3 are taken from the Unsloth repo. For a thesis, redraw these yourself — both for copyright/attribution hygiene and because [1] (a GitHub repo) is a weak source for conceptual diagrams. Cite the original papers (Christiano et al. for RLHF, Schulman et al. for PPO, Shao et al. for GRPO) for the concepts.
3. did GRPO teach the model to generate good strategies, or did it collapse onto one safe template that happens to score positive rewards on most tickers?
4. does the fine-tuned model generate valid/profitable strategies for unseen tickers?
<!-- 5. *No explicit research questions, and a Problem Definition that doesn't define the problem -->
<!-- 6. *Missing hyperparameters undermine reproducibility -->
7. *"The 30 constituents of the DJIA" — as of what date?

## Examiner Questions

1. Show me the diversity of generated strategies
2. Why should I be impressed by profitability that loses to buy-and-hold? 
3. How do you know this isn't memorization of the training tickers? 

---



