# My Python Learning Philosophy

A personal guide for how I approach learning Python.
When I feel lost, burned out, or tempted to take shortcuts — I re-read this.

---

## Core Principle

**Active learning, not passive reading.**

Reading code is not learning code. Every concept must go through this loop:

> Read → Type → Break → Fix → Apply

1. **Read** the explanation once.
2. **Type** the examples myself — never copy-paste.
3. **Break** them intentionally (change values, remove lines, see errors).
4. **Fix** the errors and understand *why* they happened.
5. **Apply** the concept to a tiny problem of my own.

Slower per concept, but I actually retain it.

---

## Daily Routine (60–90 minutes)

| Time   | Activity                                       |
|--------|------------------------------------------------|
| 15 min | Read the day's topic in the repo               |
| 25 min | Type out and run every example myself          |
| 25 min | Do Level 1 and Level 2 exercises               |
| 15 min | Update `progress.md` with what clicked / fuzzy |

Skip Level 3 if tired. Better to do one day fully than half-do two.

---

## Three Non-Negotiable Habits

### 1. Type, don't copy
My syntax weakness is muscle memory.
The only way to build muscle memory is repetition with my own hands.

### 2. Read errors before Googling
Sit with the error for 2 minutes. Try to figure it out.
Python's errors are surprisingly readable.
This is how debugging intuition develops.

### 3. Explain it out loud
After learning a concept, pretend I'm teaching someone who's never coded.
If I can't explain it plainly, I don't really know it yet.

One Python file per day. By the end of 30 days, this is a real portfolio.

---

## Daily Git Workflow

After each study session:

1. Update `progress.md` and save code in `my-exercises/`
2. Save everything (`Ctrl+S`)
3. Open terminal (`` Ctrl+` ``) and run:
git add .
git commit -m "Day XX: Topic Name"
git push

Three commands, ~30 seconds. Daily green squares. Real portfolio building.

---

## Spaced Repetition

I will forget things. That's biology, not failure.

- **End of each day:** redo one exercise from 2–3 days ago (5 min)
- **End of each week:** mini-project combining the week's concepts (30 min)

Combining concepts is where real understanding happens.

---

## When I Get Stuck

In this exact order:

1. Read the error message (2 min)
2. Re-read the relevant section in the repo (5 min)
3. Try one small experiment to test understanding (5 min)
4. *Then* ask for help or search online

Struggling for 10–15 minutes alone is when learning actually happens.
Skipping that struggle = skipping the learning.

---

## Reality Checks

Honest truths to remember on hard days:

- I will forget syntax constantly. Every working programmer Googles syntax daily.
- I will feel stupid sometimes — especially around Classes (Day 21) and Pandas (Day 25). That's growth.
- Some days I'll do 20 minutes and stop. That's better than zero.
- **Consistency beats intensity.**
- I won't feel "ready" for projects. Nobody does. Build them anyway.

---

## When to Build Projects

- **Days 14–20:** No standalone projects. Just exercises + weekly mini-projects (15–30 min).
- **Days 21+:** Start one real portfolio project.
- **By Day 25 (Pandas):** Ready for something like analyzing a Kaggle dataset.

The single biggest differentiator: **building small things consistently.**

---

## The Long View

Why this matters:

- **Now → Week 12:** Python fundamentals (this repo)
- **Months 4–6:** Data science stack (NumPy, Pandas, Matplotlib, basic ML)
- **Months 6–12:** AI engineering (LLM APIs, RAG, agents)
- **Throughout:** Build projects, push to GitHub, learn Git deeply

This repo is the foundation. Treat it like one — solid, deliberate, no shortcuts.

---

## The 10 Rules

1. Type, don't copy.
2. Read errors carefully before Googling.
3. Explain concepts out loud.
4. One Python file per day in `my-exercises/`.
5. Update `progress.md` after each session.
6. Push to GitHub daily with `git add . → commit → push`.
7. Review old exercises weekly.
8. Build a mini-project every week.
9. Struggle for 10 minutes before asking for help.
10. **Consistency beats intensity.**