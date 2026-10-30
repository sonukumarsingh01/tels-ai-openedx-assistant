<div align="center">

# 🤖 TELS AI — Plug-and-play AI for Open edX

### An AI assistant that installs into any Open edX platform in minutes

**Product owner:** [TitanEd](https://github.com/TitanEd) &nbsp;·&nbsp; **My role:** Frontend Engineer (complete AI UI and rendering system) &nbsp;·&nbsp; **Oct 2026 – Present**

![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Open edX](https://img.shields.io/badge/Open%20edX-02262B?style=flat)
![Generative AI](https://img.shields.io/badge/Generative%20AI-FF6F00?style=flat)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat&logo=jest&logoColor=white)

</div>

> **Note:** TELS AI is a commercial product and its source code is private. This repository is a **project showcase** and contains no company code.

---

## 📌 The business problem

Open edX powers thousands of learning platforms, but it has **no built-in AI**. Organisations want AI help for learners and
course teams, but they **don't want to fork Open edX, rebuild their platform or migrate** to a new LMS.

## 💡 The solution: sold two ways

| | |
|---|---|
| **Inside TELS** | Included in [TELS](https://github.com/sonukumarsingh01/tels-saas-learning-platform), TitanEd's SaaS platform |
| **As a standalone plugin** | Any organisation already running **standard Open edX** installs the plugin and gets the AI, with no migration and no core changes |

## ✅ What I delivered

I built the **complete user interface and rendering system of the AI assistant in every Open edX app**: LMS, Studio and dashboards.

- **One assistant everywhere:** the same AI panel appears in every app, with no changes inside any app.
- **Rich, interactive answers:** the AI's replies appear as cards, tables, forms, progress views and action buttons, not just text.
- **Safe by design:** the AI can only show UI blocks from an approved catalogue. It can never inject code into the page.
- **Every client's brand, every language:** design-token theming, Hindi, Arabic and Spanish, and right-to-left layouts.
- **Tested:** unit tests with Jest and React Testing Library.

## 🎯 What users can do with AI

**Learners**
- Understand a lesson faster: summaries, explanations, questions about a lesson or the whole course.
- Practise: generated questions, a role-play coach, an exam-readiness check.
- Stay on track: goals, a personal study plan, upcoming deadlines, revision sheets and progress.

**Course teams and admins**
- An AI forum assistant that answers and moderates course discussions.
- AI reports on learning impact, at-risk learners, deadlines and course health.

## 📈 Business impact

- **A new product line:** AI sold to any Open edX client, not only TELS customers.
- **Zero-risk install:** a plugin, with no fork and no core change, so upgrades stay safe.
- **Brand-ready:** each client sees the AI in its own colours and language.

## 🏗️ How it's built

```
 Any Open edX app (LMS · Studio · Dashboards)
        │  plugin slot (no core change)
        ▼
 ┌───────────── AI assistant UI (my work) ─────────────┐
 │ Launcher · Panel · Conversation · Streamed answers   │
 │ Block renderer: card · table · form · action · progress │
 │ Design tokens · i18n (hi, ar, es) · RTL               │
 └───────────────────────┬──────────────────────────────┘
                         │ stream of typed JSON events
                         ▼
               TELS AI backend (Django plugin)
```

**Tech:** React, Paragon, Frontend Plugin Framework, streaming APIs, react-intl, design tokens, Jest, React Testing Library.

---

<div align="center">

**Sonu Kumar** · Frontend Engineer · [LinkedIn](https://www.linkedin.com/in/dr-sonu-kumar/) · [GitHub](https://github.com/sonukumarsingh01)

</div>
