# 🃏 Flashy — English to Urdu Flashcard App (Python)

A desktop flashcard app built with Python and Tkinter that helps you learn new English words and their Urdu meanings. Each card flips automatically, and the app keeps track of which words you still need to practice.

## What it does

- Shows a random English word on the front of a card
- Automatically flips the card after a few seconds to reveal the Urdu meaning
- Click ✅ if you already know the word — it gets removed from your learning list
- Click ❌ if you don't know it yet — it stays in the list and a new card is shown
- Remembers your progress, so words you already know won't show up again next time you run the app

## Files in this project

| File / Folder | What it does |
|----------------|---------------|
| `main.py` | Runs the app — shows cards, flips them, and tracks your progress |
| `data/english_words.csv` | The full list of English–Urdu word pairs |
| `data/words_to_learn.csv` | Auto-created file that tracks which words you still need to learn |
| `images/` | Card front/back images and the ✅ / ❌ button icons |

## How to run it

1. Make sure you have Python installed on your computer
2. Install the `pandas` library if you don't already have it:

```bash
pip install pandas
```

3. Download or clone this repository
4. Open a terminal in the project folder and run:

```bash
python main.py
```

Make sure the `data/` and `images/` folders stay in the same location as `main.py`, since the app loads files from them.

## How to use it

- A card appears showing an English word
- Wait a few seconds for it to flip and show the Urdu meaning (or just try to recall it yourself first!)
- Click ✅ if you knew it, or ❌ if you didn't — either way, a new card appears

## Requirements

- Python 3
- `pandas` library
- `tkinter` (comes built-in with Python, no extra installation needed)

## About

This project was built as a way to practice GUI development with `tkinter`, working with data using `pandas`, and building something genuinely useful — a personal vocabulary trainer.
