# CS50AI: Minesweeper AI Agent

An Artificial Intelligence agent built to play Minesweeper perfectly using **propositional logic** and **logical inference**. This project was completed as part of Harvard University's CS50’s Introduction to Artificial Intelligence with Python.

---

## 🚀 Project Overview
Unlike humans who rely on intuition or guessing, this AI agent tracks the state of the Minesweeper board using mathematical logic sentences. It converts information from revealed cells into knowledge blocks and dynamically infers which cells are guaranteed safe or contains mines.

### Core Concepts Used:
* **Knowledge Representation:** Representing the board state as logical sentences: `{cells} = count`.
* **Inference Engine:** Automatically drawing new conclusions by identifying when one sentence is a subset of another.
* **Propositional Logic:** Making safe moves deterministically based on facts, and calculating probabilities only when a random move is strictly required.

---

## 🔒 Academic Honesty Notice
To strictly comply with **CS50's Academic Honesty policy**, the source code files (`minesweeper.py`) have been intentionally omitted from this public repository to prevent plagiarism. 

*The fully functioning code is hosted in a private repository and can be provided to university admissions officers or academic reviewers upon direct request.*

---

## 💻 Tech Stack
* **Language:** Python 3
* **Libraries:** Pygame (for the graphical user interface visualization)
