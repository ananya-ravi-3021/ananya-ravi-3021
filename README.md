<h1 align="center">Hi, I'm Ananya 👋</h1>

<p align="center">
  Software engineer who kept building things about food, then went to grad school for AI
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Columbia-MSAI-004b87?style=flat-square" />
  <img src="https://img.shields.io/badge/NUS-B.Comp%20CS-ef7c00?style=flat-square" />
  <img src="https://img.shields.io/badge/Based%20in-NYC-333?style=flat-square" />
</p>

---

### 🌱 Currently

Studying AI at **Columbia** (inaugural MSAI cohort), concentrating in **AI for Finance & Operations**.
Before that: two years shipping payments infrastructure at **PayPal**.

Interested in the unglamorous half of ML: what models do when the data shifts under them, and how to notice before someone else does.

---

### 💼 Where I've Worked

| | | |
|---|---|---|
| 🟦 **PayPal** | Software Engineer, Global Solutions Engineering | 2024 – 2026 |
| 🔬 **NUS AI Lab** | Research Assistant | 2022 – 2024 |
| 🎓 **NUS School of Computing** | Teaching Assistant, CS2100 Computer Organization | 2022 |

**At PayPal I:**
- 🔌 Built an **MCP server** in Python (FastMCP) so engineers could pull remote financial data straight from their IDE instead of clicking through an internal portal. It became a daily-driver tool for the team.
- ☕ Led **Java backend** work on an electronic verification platform that replaced a manual onboarding process across multiple countries.
- 📊 Wired up a **webhook API** piping onboarding metrics into BigQuery for compliance analytics.
- ⚛️ Tuned **React / Next.js** checkout components for high-growth commerce markets.

---

### 🌏 Internships

| | | |
|---|---|---|
| 🏦 **HSBC** | Summer Technology Analyst, Securities Services | 2023 |
| 🟦 **PayPal** | Software Engineering Intern → 🏆 *#1 Intern* | 2022 |
| 🛒 **GrowSari** | Data Science Intern | 2021 |

<sub>HSBC: built a client data-lineage report in Looker Studio on GCP, plus a Python pipeline to auto-ingest client API responses. · PayPal: shipped Java/Kotlin features on the Android digital card app, including a new rewards flow. · GrowSari: sales forecasting with linear regression and SVR for inventory planning.</sub>

---

### 🍜 My Two Undergrad Projects (Both, Somehow, About Food)

#### 🥄 Fixipe 
> **iOS recipe adapter** · Swift · Vision Framework · Python + Firebase · NUS Orbital, 2021

Point your camera at a recipe. Fixipe reads it with on-device OCR, checks the ingredient list against your allergies and dietary restrictions, and suggests swaps for anything you can't eat. 

#### 🧪 [Cross-Modal Image-Recipe Retrieval](https://github.com/ananya-ravi-3021/cross-modal-image-recipe-retrieval)
> **Final year thesis** · PyTorch · multi-label classification · NUS School of Computing, 2023/24

Fixipe needed a recipe. What if you only have the plate? This one predicts **10 allergen labels straight from a food photo**, with the ground truth derived from recipe ingredients (that's the cross-modal part).

Tried a ResNet baseline, class-specific residual attention, and a graph convolutional network over a label co-occurrence graph, plus asymmetric losses to handle an imbalanced label set.

Best result: **60.9% mAP**. The most useful finding was a negative one, though. The fancy architectures lost to the simple one, because ingredients in a cooked dish are mixed in rather than sitting in tidy regions of the image, so per-region attention had nothing to attend to. Fixing the class balance mattered far more than any model I tried.

---

### 🧰 Toolbox

```
ML        PyTorch · scikit-learn · transformers · GCNs · multi-label & semi-supervised learning
Languages Python · Java · TypeScript · Kotlin · Swift · C · SQL
Building  React · Next.js · FastMCP · FastAPI · Firebase
Data      GCP · BigQuery · Looker Studio · Jupyter
```

---
