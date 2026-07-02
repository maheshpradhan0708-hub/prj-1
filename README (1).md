# 🧑‍💻 Personal Data Collector

A beginner-friendly Python console program that collects a user's personal
details, reveals the **data type** and **memory address** of each stored
value, and prints a friendly farewell message.

```
****************************************
welcome to the persnoal data collector
****************************************
```

---

## 🎯 Objective

The goal of this practice script is to help reinforce core Python
fundamentals for someone new to the language, specifically:

- Taking user input with `input()`
- Type casting (`int()`, `float()`, `str()`)
- Inspecting an object's data type with `type()`
- Inspecting an object's memory location with `id()`
- Formatting and printing multi-part strings to the console

---

## 📋 Problem Statement

Write a program that:

1. Greets the user with a banner/welcome message.
2. Asks the user to enter four pieces of personal data:
   - Name (text)
   - Age (whole number)
   - Height (decimal number)
   - Favourite number (whole number)
3. For **each** piece of data collected, displays:
   - The value entered
   - Its Python data type (`str`, `int`, `float`)
   - Its memory address in the current run (via `id()`)
4. Ends the program with a thank-you banner.

---

## 🔄 Program Flow

```
┌────────────────────────────┐
│  Print welcome banner       │
└──────────────┬──────────────┘
               ▼
┌────────────────────────────┐
│  Prompt: Enter the name     │──▶ store as string
└──────────────┬──────────────┘
               ▼
┌────────────────────────────┐
│  Prompt: Enter your age     │──▶ cast to int
└──────────────┬──────────────┘
               ▼
┌────────────────────────────┐
│  Prompt: Enter your height  │──▶ cast to float
└──────────────┬──────────────┘
               ▼
┌────────────────────────────┐
│  Prompt: enter the number   │──▶ cast to int
└──────────────┬──────────────┘
               ▼
┌────────────────────────────┐
│  Print each value along     │
│  with type() and id()       │
└──────────────┬──────────────┘
               ▼
┌────────────────────────────┐
│  Print thank-you banner     │
└────────────────────────────┘
```

---

## 🖥️ Sample Run (IDLE Shell)

```
Enter the name:mahesh pradhan
Enter your age:17
Enter your height:1.78
enter the number08
Name:  mahesh pradhan |Data type:  <class 'str'> |Memory Address: 2894115539760
Age: 17  |Data type: <class 'int'> |Memory  Address: 140727215441528
height: 1.78  |Data type: <class 'float'> |Memory  Address: 2894157153584
favourite number: 8 |Data type: <class 'int'> |Memory Adress: 140727215441240
_._._._._._._._._._._._._._._._.
THANKYOU FOR VISITING
_._._._._._._._._._._._._._._._.
```

> ⚠️ Note: Memory addresses (`id()`) will be **different every time** the
> program is run — this is expected Python behaviour, not a bug.

---

## 🛠️ Tech Stack

| Tool     | Version |
|----------|---------|
| Python   | 3.14.6  |
| Editor   | IDLE (Windows) |

---

## 🚀 How to Run

```bash
python "py pratice.py"
```

Then follow the on-screen prompts to enter your name, age, height, and
favourite number.

---

## 📌 Known Typos / Possible Improvements

These are small polish items noticed in the current output and could be
cleaned up in a future version:

- [ ] "persnoal" → "personal" (welcome banner)
- [ ] "THANKYOU" → "THANK YOU"
- [ ] "Memory Adress" → "Memory Address" (consistency across all four prints)
- [ ] Add input validation (e.g., reject non-numeric age/height)
- [ ] Add spacing after prompts, e.g. `"enter the number: "` instead of `"enter the number"`

---

## ✍️ Author

**Mahesh Pradhan**
*Python practice project — Project 08*
