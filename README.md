# 🍔 Food Delivery App – Agile Scrum Simulation  

> **Course:** 23CSE3012 – Agile Software Development  
> **Team Members:** Tanmay Kshirsagar & Team  
> **Roles:** Product Owner | Scrum Master | Developers (4)

---

## 📖 Project Overview  
This repository documents our **Agile Software Development** mini-project — *Food Delivery App* — implemented using the **Scrum framework**.  
The project was executed over multiple sprints and demonstrates the **complete Agile lifecycle** from planning to CI/CD integration.  

We used **Trello** for sprint management and **GitHub** for version control and continuous integration simulation.

---

## 🧩 Scrum Framework Implementation  

| Scrum Role | Responsibility |
|-------------|----------------|
| **Product Owner** | Defines vision, manages Product Backlog |
| **Scrum Master** | Facilitates process, removes blockers |
| **Developers** | Build features, test & integrate increments |

---

## 🚀 Agile Artifacts  

| Artifact | Description |
|-----------|-------------|
| **Product Backlog** | Contains all user stories with priorities and story points |
| **Sprint Backlog** | Subset of Product Backlog selected for current sprint |
| **Increment** | Working deliverable after each sprint (UI mockups, Trello progress) |

📂 Files included in this repository:
- `product_backlog.md`
- `sprint_backlog.md`
- `cart_notes.md`
- `.github/workflows/ci.yml` (for CI demonstration)

---

## 🧠 Tools & Technologies  
- **Trello** → Sprint planning & progress tracking  
- **GitHub** → Version control & CI/CD workflow  
- **Excel** → Burn-down & Burn-up charts  
- **Markdown** → Documentation of Agile artifacts  

---

## 📊 Project Highlights  
✅ Implemented Agile estimation using **Planning Poker** and **Story Points**  
✅ Created and prioritized backlogs based on **INVEST principle**  
✅ Visualized sprint progress with **Burn-down/Burn-up charts**  
✅ Demonstrated collaboration and automation via **GitHub Actions CI**  
✅ Reflected on improvements during **Sprint Retrospectives**  

---

## 🧾 Agile-DevOps Integration (CI/CD Demo)  
A simple **GitHub Actions** workflow is used to simulate **Continuous Integration (CI)** by automatically checking repository structure on every push or pull request.

```yaml
# .github/workflows/ci.yml
name: Basic CI Demo
on: [push, pull_request]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - name: Verify Files
        run: ls -la
