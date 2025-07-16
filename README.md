# Leonardo's GitHub Profile  

<div align="center">
  <img src="profile_gif.gif" alt="me" width="400">
</div>

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-Profile-informational?style=flat&logo=linkedin&logoColor=white&color=0077B5)](https://www.linkedin.com/in/leonardo-guerra-leo/)  

Hi! I'm **Leo**, a quant and engineer working at the intersection of **financial mathematics**, **machine learning**, **market microstructure modeling**, and **applied NLP / generative AI**. I enjoy taking noisy, high‑frequency or unstructured data and building models, tooling, and research prototypes that can move toward systematic decision‑making. 🔥

---

## Research Themes (current interests)

- **Market Microstructure & Simulation** – modeling message‑level order flow and synthetic LOB environments.
- **Statistical & ML Signal Construction** – short‑horizon prediction, risk‑aware transforms, portfolio inputs.
- **NLP Interfaces for Finance** – mapping language (risk prefs, docs, news) into structured model hooks.
- **Alt / Unstructured Data Engineering** – images, docs, sensor series → features useful for modeling.


---

## Projects & Works

### Computational Finance Master Thesis
**Limit Order Book Simulation with AI / Gen‑AI‑inspired Architectures**  
This research explored applying deep / LLM‑inspired sequence models to simulate high‑frequency Limit Order Book (LOB) dynamics.  
- Benchmarked model families (incl. State‑Space Model variants in JAX) for multi‑event LOB streams.  
- Evaluated event‑type mix, inter‑arrival timing, order‑size distributions, and mid‑price behavior.  
- Investigated and mitigated mode collapse during multi‑step rollouts via sampling strategy + regularization.  
- Proposed latent/embedding encodings to better represent sparse message vocabularies.  
- Collaboration with industry; **code not publicly released**.

[**Read Abstract (PDF)**](https://github.com/leoguerra97/leoguerra97/blob/main/Abstract_Leonardo_Guerra.pdf)

**Tags:** `Finance` `Deep Learning` `Generative Models` `Market Simulation` `Python` `JAX`

---

### HangmanBERT
An interactive AI‑driven **Hangman** game that combines **BERT** and a **statistical n‑gram prior** to update word probabilities as letters are revealed.  
- Uses an n‑gram frequency model as an initial prior over candidate words.  
- Applies BERT contextual scoring to refine probabilities with partial information.  
- Illustrates sequential Bayesian‑style updating logic that parallels streaming inference problems.

Repo: https://github.com/leoguerra97/HangmanProject

**Tags:** `NLP` `BERT` `Statistical Models` `Game Development` `Python`

---

### StockBERT_Advisor – Reinforcement Learning Trading Agent w/ NLP Module
Prototype framework where a **Reinforcement Learning agent** adapts portfolio actions based on **natural‑language risk instructions** parsed with a fine‑tuned BERT model.  
- Text input (risk tolerance, constraints) mapped into agent behavior modifiers.  
- Trades across three assets (Google, S&P 500, Gold) with buy/sell/hold actions.  
- Incorporates **Sharpe ratio** in reward shaping for risk‑adjusted decisions.

Repo: https://github.com/leoguerra97/StockBERT_advisor

**Tags:** `Reinforcement Learning` `NLP` `Financial Engineering` `Deep Learning`

---

### Markowitz Optimization and Bank Default Prediction
Two related finance modeling exercises in a single repository.  
1. **Markowitz Optimization**  
   - Rolling‑window portfolio construction experiments.  
   - Constraint scenarios: no‑short, regularization (Lasso / Ridge) to stabilize estimates.  
   - Visualizes efficient frontier movement over time.  
2. **Bank Default Prediction**  
   - Builds and compares models to flag potential bank defaults.  
   - Includes diagnostic and interpretability visualizations.

Repo: https://github.com/leoguerra97/Markowitz_and_Default

**Tags:** `Finance` `Optimization` `Predictive Modeling` `Visualization`

---

### Polimi Master Thesis: *Heartfelt Words* – ECG Captioning with DL
Used language modeling to generate structured clinical text from ECG signals.  
- **Encoder–decoder** architecture: ResNet‑style signal encoder + modified GPT‑2 text decoder.  
- Generated narrative/diagnostic captions from time‑series inputs.  
- Evaluated with BLEU scores and qualitative assessment.  
- Explored multilingual captioning (English / German datasets).

Repo: https://github.com/leoguerra97/HeartfeltWords

**Tags:** `Deep Learning` `NLP` `ECG Captioning` `Medical AI` `GPT-2` `ResNet`

---

### Skindrape
Demo pipeline for turning raw garment images into structured, ready‑to‑list product entries.  
- Image segmentation to isolate garments from backgrounds.  
- **OpenAI API** used to extract structured metadata, classify items, and generate descriptions.  
- **Node.js front‑end** for uploads, processing, and gallery management.

Repo: https://github.com/leoguerra97/skindrape

**Tags:** `Image Processing` `Deep Learning` `OpenAI API` `Node.js` `Frontend`

---

### Artificial Neural Networks & Deep Learning Project
A set of applied DL exercises (TensorFlow) spanning multiple data modalities.  
- **Image Classification** (ResNet): crops vs weeds vs ground.  
- **Image Segmentation** (U‑Net) for agri imagery.  
- **Visual Question Answering (VQA)** pipeline combining image features with an LSTM‑based language component.

Repo: https://github.com/leoguerra97/ANN_Project

**Tags:** `Deep Learning` `TensorFlow` `Image Classification` `ResNet` `U-Net` `NLP` `LSTM` `VQA`

---

### Contact
If you work in quantitative research, systematic trading, or ML for markets and want to chat, feel free to reach out on LinkedIn or email me. Happy to discuss microstructure modeling, ML pipelines, and data engineering.

