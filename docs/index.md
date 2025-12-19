# Welcome to the Open Data Engineering Academy

---
**From Zero to Engineer: A structured, open-source curriculum for the modern Data Engineer.**

## 🚀 Why This Exists

Data Engineering is notoriously difficult to break into. The resources are scattered: one tutorial teaches you Python syntax, another teaches you a specific tool like Spark, but very few explain **how it all fits together**.

We created the **OpenData Engineering Academy** to solve "Tutorial Hell."

We believe that:

1.  **Concepts > Tools:** Tools change every year. The fundamentals of data movement do not.
2.  **Context is King:** You cannot learn SQL in a vacuum; you need to know *where* that SQL runs and *why*.
3.  **Knowledge Should Be Free:** Gatekeeping technical skills hurts the industry. We learned the hard way so you don't have to.

---

## 🗺️ How to Use This Academy

This site is structured like a university curriculum. We have broken the vast world of Data Engineering into manageable **Terms**.

* **Term 1: The Foundation** - Mental models, the command line, and the "why" behind the code.
* **Term 2: The Toolbelt** - Python and SQL specifically for data movement.
* **Term 3: The Pipeline** (Coming Soon) - Orchestration, transformation, and building your first real project.

We recommend reading linearly from **Term 1**, as later concepts build heavily on earlier ones.

---

## 📝 A Guide to Our Notes

Throughout this course, you will see different "blocks" of text. Here is a legend of what they mean, so you know when to read carefully and when to pick up your keyboard.

### 1. General Information
We use blue boxes for context, extra history, or "good to know" facts that aren't critical to the core lesson but help paint the bigger picture.

> [!INFO]
> **Did you know?**
> The term "Data Engineering" only became popular around 2011. Before that, we were mostly called "ETL Developers" or "BI Engineers."

### 2. Code & Syntax
When we are discussing code structure, folder layouts, or specific syntax, we will use the standard code block.

> [!CODE] Syntax Example
> When you see a block like this, pay attention to the indentation and structure.
> ```python
> def hello_world():
>     print("Data Engineering is cool")
> ```

### 3. Warnings & Gotchas
Pay close attention here. These orange or red boxes highlight common mistakes, production errors, or "traps" that beginners often fall into.

> [!WARNING] Production Hazard
> Never hard-code your passwords in a Python script! We will teach you how to use Environment Variables instead.

> [!ERROR] Critical Concept
> If you delete the production database, there is no "Undo" button. Always back up your data.

### 4. Homework & Self-Study
Data Engineering is a practical skill. You cannot learn it just by reading. When you see these purple blocks, it is time to stop reading and start doing.

> [!EXAMPLE] Homework: Set up your Environment
> **Task:** Open your terminal and create a new directory called `de-academy`.
>
> 1. Open Terminal/Command Prompt.
> 2. Type `mkdir de-academy`
> 3. Verify it was created with `ls` (Mac/Linux) or `dir` (Windows).

---

## 🏁 Ready to Start?

There is no software to install yet. Just bring your curiosity.

[Start Term 1: The Foundation](term-1/101-data-engineering/intro-to-data-engineering/01-what-is-data.md){ .md-button .md-button--primary }