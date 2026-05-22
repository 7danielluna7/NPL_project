# 🐺 Finn the Wolfhound: A Data-Driven Dog Story 📊

## 📖 The Big Question
Did 19th-century authors write dogs as actual animals, or just furry humans with anxiety? 

In 2002, theorist Teresa Mangum argued Victorian writers threw fictional pets into the wilderness to project human fears (like aging and isolation) onto them—ignoring that dogs descend from wolves and should *thrive* there! I used **Natural Language Processing (NLP)** and **statistics** on *Finn the Wolfhound* to see if the math backs her up.

## 🔬 The Methodology
I built an end-to-end NLP pipeline in R to track Finn's emotional rollercoaster:
* **Text Processing:** Extracted text via Project Gutenberg, aligned chapters, and used the Snowball Algorithm to stem words.
* **Sentiment Analysis:** Mapped the book's emotional tone using the **NRC Emotion Lexicon**, tracking "Trust" vs. "Fear."
* **The Math:** Split the book into "Domestic" (Master present) and "Wild" (Master absent) environments, then ran a Pearson’s Chi-Squared test. 

## 🏆 The Verdict
Spoiler alert: Mangum was right! We confidently rejected the null hypothesis.

The data proves the author ignored Finn's inner wolf to maximize human drama. The emotion of "Trust" is 100% glued to the master. The second Finn is isolated in the wild, "Trust" plummets and "Fear" mathematically skyrockets. 

## 💻 Tech Stack
* **Language:** R 
* **Libraries:** `dplyr`, `tidytext`, `SnowballC`, `ggplot2`, `wordcloud`, `posterdown`

## 🎨 The Poster
Click the image below to view the high-resolution academic poster, complete with charts and the final mathematical proof!

[![Finn the Wolfhound Poster Preview](poster_preview.png)](poster.pdf)

---
