# mini-RAG-model
How RAG works in 5 steps? A working mini-model for our Machine Learning Presentation.

Interactive notebook from our talk on **Lewis et al. (2020), "Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks"**
(Group 7 · Advanced Seminar in Machine Learning · TUM, Nov 2026).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/beshbarmoq/mini-RAG-model/blob/main/RAG_live_demo.ipynb)

**How to play:** open in Colab → `Runtime → Change runtime type → T4 GPU` → `Runtime → Run all` (first run downloads ~1.5 GB, 2–4 min).
Then change the questions, edit the handbook, or plant your own fake facts.

What's inside: a mini-RAG over a fictional company handbook, step by step: 0 Index → 1 Encode → 2 Retrieve → 3 Augment → 4 Generate → 5 Combine,
plus two experiments: swapping a document (no retraining) and sneaking in a wrong fact.

Models: DPR (`facebook/dpr-*-multiset-base`) as retriever, Flan-T5 as generator. Nothing is trained – the notebook shows the mechanism, not the paper's numbers.
"Example GmbH" is made up.
