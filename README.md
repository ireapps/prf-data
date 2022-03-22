# HHS Provider Relief Fund data
[A folder full of state-level CSVs](state-data), pulled and split on 2022-03-22, and a Jupyter notebook with some Python code to poke at the HHS COVID-19 Provider Relief Fund data.

## Running the notebook
First, [install the latest version of Python3](https://docs.google.com/document/d/1cYmpfZEZ8r-09Q6Go917cKVcQk_d0P61gm0q8DAdIdg/edit#), if you haven't already. Then:
- Clone or download/unzip this repo onto your machine
- `cd` into that folder
- `python3 -m venv env` (or `python -m venv env`, on a PC)
- `source env/bin/activate` (or `.\env\Scripts\activate` on a PC)
- `pip install -r requirements.txt`
- `jupyter notebook`