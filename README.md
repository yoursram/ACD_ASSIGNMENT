# Automata Theory: DFA, NFA & NFA to DFA Conversion

A clean Python implementation of core Automata Theory concepts: simulating Deterministic Finite Automata (DFA), Nondeterministic Finite Automata (NFA), and converting an NFA to a DFA using the Subset Construction algorithm.

---

## 📌 Features

- **DFA Simulator**: Step-by-step state traversal, transition validation, and string acceptance checking.
- **NFA Simulator**: Supports multiple active branches, epsilon ($\epsilon$) transitions, and $\epsilon$-closure computation.
- **NFA to DFA Converter**: Implements the Powerset / Subset Construction method to generate an equivalent minimal DFA.
- **Zero Dependencies**: Built entirely using pure Python 3 standard library.

---

## 🛠️ Included Modules

| Module | Description | Key Concept |
|---|---|---|
| **1. DFA Simulator** | Processes input strings across deterministic state transitions. | $M = (Q, \Sigma, \delta, q_0, F)$ |
| **2. NFA Simulator** | Tracks parallel active states and non-deterministic paths. | $\delta: Q \times (\Sigma \cup \{\epsilon\}) \rightarrow \mathcal{P}(Q)$ |
| **3. NFA → DFA** | Converts an NFA with/without $\epsilon$-transitions to a DFA. | Subset Construction |

---

## 🚀 Quick Start

### Run in Google Colab / Jupyter Notebook

1. Open `ACD_1.ipynb` in **Google Colab** or launch it locally via **Jupyter Notebook**:
   ```bash
   pip install notebook
   jupyter notebook ACD_1.ipynb

   Execute the notebook cells sequentially.

Follow the interactive prompts to define your alphabet, states, transitions, and test strings.


🎥 Video Demonstration
A walkthrough and code explanation video is available here:
https://drive.google.com/file/d/1ma0SRyuXACDGc-UrFE4Ch2m1zSE9gGgH/view?usp=sharing

📂 Repository Structure
.



├── ACD_1.ipynb      # Main Jupyter/Colab notebook with all implementations

└── README.md        # Project documentation




👤 Author
Chandragiri Ramkumar

Automata & Compiler Design (ACD)
