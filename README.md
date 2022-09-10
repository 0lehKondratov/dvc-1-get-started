### Data Version Control is a data and ML
https://github.com/iterative/dvc.org/

# Lesson 1 tutorial: Get started 
**ML REPA School course**: Machine Learning experiments reproducibility and engineering with DVC

## 1. Clone this repository

```bash
git clone https://gitlab.com/7labs.ru/tutorials-dvc/dvc-1-get-started.git
cd dvc-1-get-started
```

## 2. Create and activate virtual environment

Create virtual environment named `dvc` (you may use other name)
```bash
python3 -m venv dvc-venv
source dvc-venv/bin/activate
```

## 3. Install python libraries

```bash
pip install -r requirements.txt
```

## 4. Add Virtual Environment to Jupyter Notebook

```bash
python -m ipykernel install --user --name=dvc-venv
```

## 5. Configure ToC for jupyter notebook (optional)

```bash
sudo jupyter contrib nbextension install
jupyter nbextension enable toc2/main
```

## 6. Run and follow Jupyter Notebook `dvc-1-get-started.ipynb` for instructions:

```bash
jupyter notebook
```
