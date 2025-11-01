# Defense Mechanisms on SVM Model Against Poisoning Attacks

This repository contains Jupyter notebooks and experiments exploring defenses for Support Vector Machine (SVM) models against poisoning attacks. The notebooks demonstrate attack scenarios, defense techniques, evaluation metrics, and reproducible experiments.

## Repository structure

- Jupyter notebooks (.ipynb) — experiments, data loading, attack implementations, defenses, and evaluation.
- data/ (optional) — datasets used by notebooks (if included).
- notebooks/ (optional) — organized notebooks if you separate them into a folder.
- requirements.txt (optional) — pinned Python dependencies for reproducibility.

## Key contents

- Poisoning attack examples against SVM classifiers
- Defense strategies such as:
  - Data sanitization and outlier removal
  - Robust training procedures and regularization strategies
  - Influence-based filtering and sample weighting
- Evaluation code for measuring:
  - Accuracy degradation under attack
  - False positive / false negative changes
  - Robustness across different attack strengths and poisoning rates

## Requirements

- Python 3.8+
- Jupyter
- scikit-learn
- numpy
- pandas
- matplotlib
- seaborn

If you prefer, create a virtual environment for reproducibility.

## Installation

1. Clone the repository:

   git clone https://github.com/naggar023/Defense-Mechanisms-on-SVM-model-against-Poisoning-Attack.git
   cd Defense-Mechanisms-on-SVM-model-against-Poisoning-Attack

2. Create and activate a virtual environment:

   python -m venv venv
   # macOS / Linux
   source venv/bin/activate
   # Windows (PowerShell)
   .\venv\Scripts\Activate.ps1

3. Install dependencies:

   - If a requirements.txt file is present:
     pip install -r requirements.txt
   - Otherwise install common dependencies:
     pip install jupyter scikit-learn numpy pandas matplotlib seaborn

## Usage

- Start Jupyter and open notebooks:

  jupyter notebook

- Each notebook contains explanations, parameters, and cells to run attacks, defenses, and evaluation. Run cells in order to reproduce experiments.

## Recommendations for reproducible experiments

- Add a `requirements.txt` with pinned versions.
- Use random seeds in notebooks (e.g., numpy.random.seed and scikit-learn random_state) for reproducibility.
- If notebooks depend on external datasets, add a `data/` README explaining how to download or prepare them.

## How to contribute

Contributions are welcome. Suggested steps:

1. Open an issue describing the proposed change or improvement.
2. Create a branch for the work.
3. Submit a pull request with a clear description, changes, and testing instructions.


## Contact

Repository owner: @naggar023
