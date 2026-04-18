# 🧠 Language & Cognition — Word Frequency Analysis

## What is this project?

This project explores **how language reflects cognition** by analyzing word patterns in classic books.
You'll discover *Zipf's Law* — a real cognitive science finding that says a small number of words
make up most of what we say — and visualize it with real data.

---

## What you'll learn

- Loading and cleaning text data in Python
- Counting and sorting words with `pandas`
- Plotting distributions with `matplotlib`
- Understanding Zipf's Law (cognitive science concept)
- Building a word cloud

---

## Cognitive science connection

> **Zipf's Law** states that the most common word in any language appears roughly twice as often
> as the second most common word, three times as often as the third, and so on.
>
> This isn't random — it reflects how our brains balance **effort** (we reuse common words to save
> cognitive load) with **information** (we need rare words to express specific ideas).

---

## Dataset

We use a free book from [Project Gutenberg](https://www.gutenberg.org/) — no sign-up required.

In this project: **"Alice's Adventures in Wonderland"** by Lewis Carroll.
Download link: https://www.gutenberg.org/files/11/11-0.txt

Save the file as `data/book.txt`.

---

## Project structure

```
01-language-cognition/
├── data/
│   └── book.txt          ← text you download from Gutenberg
├── notebook.ipynb        ← your main working file
└── README.md             ← this file
```

---

## How to run

1. Install dependencies (run once in your terminal):
   ```bash
   pip install pandas matplotlib wordcloud jupyter
   ```

2. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

3. Open `notebook.ipynb` and run each cell one by one.

---

## Exercises (try these after finishing the notebook)

- [ ] Try a different book from Project Gutenberg — does Zipf's Law still hold?
- [ ] Compare word frequencies between two books by different authors
- [ ] Remove character names and re-run — how does the chart change?
- [ ] Find the top 10 *content* words (nouns/verbs only) — what does the story seem to be about?

---

## Resources

- [Zipf's Law explained (Wikipedia)](https://en.wikipedia.org/wiki/Zipf%27s_law)
- [Project Gutenberg](https://www.gutenberg.org/)
- [pandas documentation](https://pandas.pydata.org/docs/)
- [matplotlib documentation](https://matplotlib.org/)

---

*Part of my data science learning journey. Skills practiced: Python, pandas, data visualization, text analysis.*
