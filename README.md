...existing code...
# Lab Assignment 1 — Analyzing and Visualizing Recursive Algorithm Efficiency

**Course:** ENCA351  
**Student:** Priyanshu Dubey  
**Date:** <fill date>

## 📌 Project Description
This project analyzes algorithm efficiency (runtime & memory) for:
- Fibonacci: Naive recursive vs Dynamic Programming
- Sorting: Merge Sort, Quick Sort, Insertion Sort, Bubble Sort, Selection Sort
- Searching: Binary Search  

We measure execution time, memory usage, plot results, and compare with expected Big-O complexities.

---

## ⚙️ Setup Instructions (Local in VS Code)

```bash
# clone repo
git clone https://github.com/priyanshu9896/algo-efficiency-mini-project-Priyanshu.git
cd algo-efficiency-mini-project-Priyanshu

# create venv
python3 -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\Activate.ps1

# install dependencies
pip install -r requirements.txt

# register kernel
python -m ipykernel install --user --name algo-venv --display-name "Python (algo-venv)"
```

Open **VS Code → Notebook → select kernel `Python (algo-venv)` → run all cells.**

---

## 🚀 Run in Google Colab

At the top of the notebook, add:

```python
!pip install numpy matplotlib memory_profiler psutil
%load_ext memory_profiler
```

Then run all cells.

---

## 📂 Repo Structure

* `algo_analysis_notebook.ipynb` — main analysis notebook
* `requirements.txt` — dependencies
* `images/` — saved plots & CSVs
* `.gitignore` — ignores cache & venv

---

## ✅ Evidence to Collect

1. Screenshot: VS Code terminal after `pip install -r requirements.txt`
2. Screenshot: VS Code kernel = `Python (algo-venv)`
3. Screenshot: Notebook execution results + plots
4. Screenshot: GitHub repo structure with notebook, README, requirements, images

---

## 📖 Citations

* CLRS: Introduction to Algorithms
* Python docs: [https://docs.python.org/3/library/time.html](https://docs.python.org/3/library/time.html)
* NumPy & Matplotlib official documentation

**Course:** ENCA351 — Lab Assignment 1  
**Project:** algo-efficiency-mini-project-priyanshu  
**Author:** Priyanshu Dubey  
**Date:** 27 August 2025

## Description
Compare runtime and memory characteristics of standard algorithms:
- Fibonacci (Naive recursive & DP / memoization)
- Merge Sort, Quick Sort, Insertion Sort, Bubble Sort, Selection Sort
- Binary Search (correctness test)

This notebook measures time (using `time.perf_counter`) and memory (using `memory_profiler`), plots results and saves plots in `images/`.

## Setup (local)
```bash
# inside project folder
python3 -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
python -m ipykernel install --user --name algo-venv --display-name "Python (algo-venv)"
code .
```

Open `algo_analysis_notebook.ipynb` in VS Code, select kernel **Python (algo-venv)** and run all cells.

## Files

* `algo_analysis_notebook.ipynb` — notebook with code, profiling and plots
* `images/` — saved plot images
* `requirements.txt` — dependencies
* `.gitignore`

## Evidence to collect (for setup marks)

1. VS Code terminal showing `.venv` activation and `pip install -r requirements.txt`.
2. VS Code interpreter set to `.venv` (screenshot).
3. Notebook kernel set to `Python (algo-venv)` (screenshot).
4. `pip list` output (screenshot).
5. GitHub repo page showing structure (screenshot).
6. Notebook cell outputs showing timing/memory results (screenshot).

## Citations

* Add algorithm textbook or tutorial references here (e.g., CLRS).
