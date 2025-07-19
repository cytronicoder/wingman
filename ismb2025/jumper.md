# Extending AlphaFold to make predictions across the universe of biomolecular interactions

> The high accuracy of AlphaFold 2 in predicting protein structures and protein-protein interactions raises the question of how to extend the success of AlphaFold to general biomolecular modeling, including protein-nucleic and protein-small molecule structure predictions as well as the effects of post-translational modification. In this talk, I will discuss our latest work on AlphaFold 3 to develop a single deep learning system that makes accurate predictions across these interaction types, as well as examine some of the remaining challenges in predicting the universe of biologically-relevant protein interactions.

## Questions to ask

- Which kinds of real biological targets do you most want better benchmark coverage for next, and what makes them hardest to include right now?
- AlphaFold 3 seems to lean less on big multiple sequence alignments. How did you decide that "this is enough information" without overcomplicating the model?
- When you simplified the old Evoformer into the Pairformer with lighter MSA processing, what kinds of long-range signals became harder to capture, and how did you judge that the simplicity and broader chemistry support were worth that trade-off?
- Do you see a future version of AlphaFold that can choose to dig deeper into MSAs for difficult targets while staying light for easy ones, or does that undermine the new streamlined approach?
- For difficult cases you generate many sampled models. How do you decide when you have enough seeds and are just burning compute? Could a simple diversity or disagreement measure tell you to stop?
- For multi-domain and membrane proteins, do you think bigger gains will come first from adding structural context or from more/better data?
- Right now, sampling mostly tweaks uncertain regions rather than producing clearly different functional states. What would it take to move toward generating a real set of alternative conformations on purpose?
