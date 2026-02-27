# microGPT Study Workshop

This repository contains workshop material for a hands-on study session on **microGPT**, inspired by Andrej Karpathy’s (https://karpathy.github.io/2026/02/12/microgpt/)  minimalist implementation of a GPT-style language model.

The core artifact is a Jupyter Notebook that combines:
- The minimal implementation of microGPT (as presented in the original write-up by Andrej Karpathy)
- Mathematical explanations of core concepts
- Visual illustrations and structured markdown notes
- Step-by-step conceptual breakdown of transformer training mechanics

---

## 🎯 Purpose

This repository is designed for:

- Faculty and researchers seeking conceptual clarity on transformer internals
- Students learning how large language models are implemented from scratch
- Practitioners who want a minimal, interpretable GPT training loop
- Study groups exploring attention, gradients, and backpropagation

The goal is **mechanistic understanding** of the workings of GPT model.

---

## 📂 Repository Structure

```
microGPTStudyGroup/
│
├── microGPT.ipynb # Main workshop notebook
├── image files used in the workshop notebook
└── README.md # This file
```

The notebook contains:

1. Tokenization basics  
2. Language modeling objective  
3. Embeddings  
4. Attention mechanism  
5. Chain rule in backpropagation  
6. Gradient computation  
7. Parameter updates  
8. Training loop  

---

## 🧠 Topics Covered

The notebook interleaves implementation and theory, covering:

- Tokens and vocabulary construction
- Bigram language models
- Neural language modeling
- Embedding layers
- Self-attention mechanism
- Multi-head attention (conceptual framing)
- Chain rule for deep networks
- Gradient flow
- Backpropagation mechanics
- Loss computation
- Parameter updates via gradient descent

All explanations are embedded directly alongside runnable code.

---

## ⚙️ Requirements

- Python 3.9+
- PyTorch
- Jupyter Notebook or JupyterLab

Install dependencies:

`pip install torch jupyter


## How to Use

1. Clone the repository:

git clone https://github.com/NimritaKoul/microGPTStudyGroup.git
cd microGPTStudyGroup

2. Launch Jupyter:

jupyter notebook

3. Open microGPT.ipynb and execute cells sequentially.

The notebook is structured to be read and executed top-down.


## 🧩 Pedagogical Design

This notebook is structured for workshop delivery:

Code is minimal and readable

Mathematical derivations are explained step-by-step

Key ideas are illustrated visually

Conceptual bridges are made explicit (e.g., from chain rule → gradient tensors → parameter updates)

The emphasis is clarity over optimization.

## 📌 Intended Outcome

By the end of the notebook, participants should:

Understand how a GPT-style model is built from scratch

Trace gradient flow through the network

Connect mathematical derivations to implementation

Demystify transformer training mechanics

## 📄 License

The images used in this notebook are the copyright of their original creators and are used here for educational purposes only. The code used belongs to Andrej Karpathy.


## 🙌 Acknowledgment

The implementation is based on Andrej Karpathy’s microGPT educational material : https://karpathy.github.io/2026/02/12/microgpt/.
This repository annotates the material for structured workshop delivery.




