# Hi, I'm Biba!!

Data & Analytics Intern @ Morning Brew · Incoming MS Analytics @ Georgia Tech · Knitter

---

## I got into programming through knitting. 

Knitting is just physically programming yarn based on a specified algorithm.

Consider this pattern instruction:

```
Round 4: k5, * yo, k1, yo, k4, p4, k4, rep from * around.
```

`k5` means *knit each of the next 5 stitches*. Already, you're looking at a core
programming principle: [Don't Repeat Yourself].
Five identical actions collapsed into one symbol. `rep from *` is a loop.
`yo` is a function call. The whole pattern is an algorithm — a precise,
repeatable set of instructions that produces the same output every time,
whether you're running it on size 3 needles or industrial knitting machinery.

I realized at some point that the mental model I'd built for reading patterns,
breaking down repetition, spotting abstraction, thinking in structured steps,
was the same one I needed for code. Knitting gave me a concrete intuition for
programming before I ever wrote a line of Python.

Now I build the things I used to do by hand.

My [knitting pattern generator](YOUR_REPO_LINK) takes a photo and converts it
into a to-scale colorwork chart using k-means color clustering — the same DRY
logic, just running in a Streamlit app instead of a skein of yarn.

The deeper version of that project: I'm currently hacking a **Brother KH-930e**
(a 1980s punch-card knitting machine) to accept image data directly from a
laptop via an Arduino board. The machine was designed to read physical mylar
sheets with punched holes. The Arduino intercepts the carriage position sensor,
reads the needle selection signal, and replaces the punch-card input with pixel
data decoded from a bitmap in real time. Feed it a JPEG, get back a knitted
fabric. The full pipeline runs from image → Python preprocessing → serial
communication → Arduino firmware → physical needles.

It's the most literal definition of turning code into something you can hold.

---

## What I'm working on

**@ Morning Brew** — factor analysis on newsletter ad CTR across a large dataset.
Central finding so far: specificity drives clicks, not positivity. BERT, VADER,
regression, the works.

**Brother KH-930e machine hack** — retrofitting a 1980s knitting machine with an
Arduino to accept laptop images as knitting instructions. Carriage position
sensing, real-time serial communication, bitmap-to-needle-selection firmware.
Hardware + software, physical output.

**Knitting pattern generator** — the software side of the above. Photo → colorwork
chart → row-by-row instructions, with a yarn weight size calculator built in.

**Next up** — MS in Analytics at Georgia Tech, Fall 2026.

---

## Skills

**Languages:** Python · SQL · R · C++ (Arduino)
**Libraries:** pandas · scikit-learn · matplotlib · Streamlit · NLTK · VADER · BERT  
**Methods:** Regression · A/B testing · NLP · factor analysis · data visualization  
**Hardware:** Arduino · serial communication · embedded firmware  
**Tools:** GitHub · Jupyter · VS Code

---

## Projects

| Project | What it does | Stack |
|---|---|---|
| [KH-930e Machine Hack](YOUR_REPO_LINK) | Retrofit a 1980s knitting machine to knit images from a laptop via Arduino | Python · Arduino C++ · serial comms · bitmap processing |
| [Knitting Pattern Generator](YOUR_REPO_LINK) | Upload a photo → get a colorwork knitting chart + yarn size guide | Python · Streamlit · PIL · sklearn |
| [Newsletter Ad CTR Analysis](YOUR_REPO_LINK) | What actually makes people click on newsletter ads? | Python · pandas · BERT · matplotlib |

---

## Background

🎓 BA Psychology, minor in Data Science — University of Colorado Boulder  
📐 MS Analytics (incoming Fall 2026) — Georgia Tech

The psychology degree isn't incidental. Understanding *why* people behave the
way they do, what they click, what they skip, what makes something feel worth
their time, is the same question whether you're running an experiment or
building a model.

---

## Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](www.linkedin.com/in/biba-schwendt)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:rschwendt@gmail.com)
<!--
**biiibbbaaa/biiibbbaaa** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
