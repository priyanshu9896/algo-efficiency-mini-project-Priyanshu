...existing code...
# Analyzing and Visualizing Recursive Algorithm Efficiency

**Course:** ENCA351 — Lab Assignment 1  
**Project:** algo-efficiency-mini-project-priyanshu  
**Author:** Priyanshu Dubey  
**Date:** <fill date>

## Description
Compare runtime and memory characteristics of standard algorithms:
- Fibonacci (Naive recursive & DP / memoization)
- Merge Sort, Quick Sort, Insertion Sort, Bubble Sort, Selection Sort
- Binary Search (correctness test)

This notebook measures time (using `time.perf_counter`) and memory (using `memory_profiler` + `psutil`), plots results and saves plots in `images/`.

## Setup (local)
```bash
# inside project folder
python3 -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
python -m ipykernel install --user --name algo-venv --display-name "Python (algo-venv)"
code .
Open algo_analysis_notebook.ipynb in VS Code, select kernel Python (algo-venv) and run all cells.
```

### Running in Google Colab
At the top cell in Colab add:
```python
!pip install numpy matplotlib memory_profiler psutil
%load_ext memory_profiler
```
Note: Colab environment differs from local; memory results may vary.

### Files
algo_analysis_notebook.ipynb — notebook with code, profiling and plots
images/ — saved plot images (committed if required)
requirements.txt — dependencies
.gitignore

### Evidence to collect (for setup marks)
VS Code terminal showing .venv activation and pip install -r requirements.txt.
VS Code interpreter set to .venv (screenshot).
Notebook kernel set to Python (algo-venv) (screenshot).
pip list output (screenshot).
GitHub repo page showing structure (screenshot).
Notebook cell outputs showing timing/memory results and saved images (screenshot).

### Citations
Add algorithm textbook or tutorial references here (e.g., CLRS).

---

Tools used to assist with setup:
- GitHub Copilot / automation agent: created scaffolding and applied fixes.
- Student performed algorithm analysis, wrote reflections, and ran experiments locally.

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
