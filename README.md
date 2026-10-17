# usr_exercises

Esercitazioni del corso **ml-dl** (cartella `ml-dl/`):

| Notebook | Contenuto |
|---|---|
| `00_all.ipynb` | Confronto di tutti i modelli su dataset reali (testo, strutturati, immagini) da Hugging Face |
| `01_naive_bayes.ipynb` | GaussianNB, MultinomialNB, BernoulliNB |
| `02_knn.ipynb` | KNN, scaling, cross-validation ed Elbow Method |
| `03_svm.ipynb` | SVM con kernel RBF e matrice di confusione |
| `04_decision_trees.ipynb` | Decision Tree, pruning, feature importance e Random Forest |

## Ambiente locale (venv + kernel Jupyter)

```powershell
python -m venv .venv
.\.venv\Scripts\python -m pip install -r requirements.txt
.\.venv\Scripts\python -m ipykernel install --user --name ml-dl --display-name "Python (ml-dl)"
.\.venv\Scripts\python -m jupyter lab
```

Poi in Jupyter: *Kernel → Change Kernel → Python (ml-dl)*.
`00_all.ipynb` scarica i dataset da Hugging Face alla prima esecuzione (serve connessione, nessun account).
