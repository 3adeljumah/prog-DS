# Fair Price or Overpriced? Jordan's Used-Car Market and the Shift to Electric
**Programming for Data Science (606315) – University of Petra – Phase 1 submission**
Team 7: Adel Alawneh (202310707), Hashem Alawadi (202311241), Kareem Hamad (202310836)
Repository: https://github.com/3adeljumah/prog-DS

## Contents
| File | What it is |
|---|---|
| `Proposal.pdf` | Project proposal (2 pages) |
| `Environment_Setup.pdf` | Environment setup report |
| `EDA_Notebook.ipynb` | EDA notebook, executed with all outputs |
| `EDA_Notebook.html` | The same notebook as HTML, for quick viewing |
| `requirements.txt` | Pinned dependencies |
| `data/cars_raw.csv` | JUCars-2024 raw data (Thalji, 2026, Mendeley Data, DOI 10.17632/ddcz486x5t.2, CC BY 4.0) |
| `data/cars_dictionary.csv` | Data dictionary shipped with the dataset |
| `data/brand_origin.csv` | Team-built brand → country/region lookup table (merge) |
| `data/fuel_economy.csv` | US DOE/EPA fuel-economy data (public domain), 11 columns kept (merge) |
| `data/cars_clean.csv` | Cleaned and merged output of the notebook (8,625 × 29), input to Phase 2 |

## Run
```bash
git clone https://github.com/3adeljumah/prog-DS && cd prog-DS
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter lab EDA_Notebook.ipynb        # or: jupyter nbconvert --to notebook --execute --inplace EDA_Notebook.ipynb
```
Data sources: https://doi.org/10.17632/ddcz486x5t.2 · https://www.fueleconomy.gov/feg/download.shtml
