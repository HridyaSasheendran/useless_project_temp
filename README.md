<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />

# Wordnt 🎯

## Basic Details

### Team Name: DuoX

### Team Members
- Team Lead: Fathima Maha - Government Engineering College Kozhikode
- Member 2: Hridya Sasheendran P V - Government Engineering College Kozhikode

---

## Project Description

**WORDN'T** is a simple and unnecessarily challenging word game where players have to type valid English words while avoiding randomly generated forbidden letters.

The game starts with one forbidden letter and gradually becomes more difficult by adding more forbidden letters as the player successfully survives more words. Players have limited lives and time, making their vocabulary unexpectedly stressful.

---

## The Problem (that doesn't exist)

People can normally type English words without restrictions.

This is clearly too easy.

There is absolutely no reason why someone should be allowed to use every letter of the alphabet while typing a word. WORDN'T solves this completely imaginary problem by banning random letters and making ordinary vocabulary unnecessarily difficult.

---

## The Solution (that nobody asked for)

WORDN'T randomly selects letters that the player is not allowed to use.

The player must:

- Find a real English word.
- Avoid all currently forbidden letters.
- Earn points based on word length.
- Survive with only three lives.
- Beat the 30-second timer.
- Handle an increasing number of forbidden letters.

The game begins with one forbidden letter and increases the difficulty as the player survives more words:

```text
0–2 successful words    → 1 forbidden letter
3–5 successful words    → 2 forbidden letters
6–8 successful words    → 3 forbidden letters
9–11 successful words   → 4 forbidden letters
12+ successful words    → 5 forbidden letters
