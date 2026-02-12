# Assignment 1 - Computer Intelligence

## Setup 

Clonati repository ul si dupa dati uv sync sau cum spunea acolo

```powershell
uv sync
```

Comanda va crea mediul virtual local (`.venv`) si va instala dependentele din `uv.lock`.

## Cum cred eu ca e bine sa lucram

1. Nu direct pe `main`.
2. Creati branch separat pentru fiecare task (exemplu: `feature/nume-task`).
3. Dam un nume la commit cat de cat sa intelegem ce e cu el
4. Vedem dupa aceea cum rezolvam cu merge urile

## Ce am pus in repo


- notebook-urile (`src/*.ipynb`)
- datele necesare (`data/*`)
- fisierele de mediu (`pyproject.toml`, `uv.lock`)

Nu am pus pentru ca nu cred ca trebuie modificate si se genereaza cand dam uv sync:

- `.venv/`
- cache-uri locale / fisiere temporare

## Ca sa mearga totul cum trebuie

- Evitam editarea simultana in aceleasi celule
- Inainte de commit, dati run si salvati local, am citit pe net ca nu toate mergeurile merg cum trebuie cu jupyter
- Daca apar conflicte in `.ipynb`, scriem pe grup si vedem cum le rezolvam
