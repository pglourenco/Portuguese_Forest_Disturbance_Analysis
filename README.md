# Portuguese Forest Disturbance Analysis

A university project analyzing the Portuguese Forest Disturbance Dataset. The notebook explores the data and applies data analysis and machine-learning methods. Made as part of the PACED 2024/25 course @ NOVA SST.

## Contents

- `project_Pedro_Diogo_PACED_24-25.ipynb` — project notebook
- `requirements.txt` — Python packages used by the notebook

The dataset is not included in this repository. Download it separately using the instructions below.

## Requirements

- Python 3.11 with the packages included in requirements.txt
- Jupyter Notebook

## Installation and setup

### 1. Clone or download this repository

To clone it with Git:

```bash
git clone https://github.com/YOUR-USERNAME/paced-forest-disturbance-analysis.git
cd paced-forest-disturbance-analysis
```

Alternatively, select **Code → Download ZIP** on GitHub, extract the ZIP, and open a terminal in the extracted repository folder.

### 2. Create a virtual environment

On Windows:

```powershell
py -3.11 -m venv .venv
```

Activate it:

```powershell
.\.venv\Scripts\Activate.ps1
```

If PowerShell prevents activation, you can run the environment’s Python directly with the commands below instead.

### 3. Install the Python packages

```powershell
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

### 4. Download the dataset

Download the dataset from the [original dataset repository](https://github.com/EduardoFAFernandes/portuguese-forest-disturbance-dataset).

Extract the downloaded files into the project folder. The extracted data folder must be named:

```text
portuguese-forest-disturbance-dataset-main
```

Place it beside the notebook, so the CSV files are inside that folder. Avoid an extra nested folder with the same name.

The dataset is not redistributed with this project. Check the original repository for its current terms before using or sharing the data.

### 5. Run the notebook

Start Jupyter from the project folder:

```powershell
jupyter notebook
```

Open `project_Pedro_Diogo_PACED_24-25.ipynb` in the browser and run the cells.

## Acknowledgements

This work was developed under the supervision of Prof. Carlos Augusto Isaac Piló Viegas Damásio (NOVA University Lisbon), as part of the Erasmus Mundus Joint Master in ChEMoinformatics+, co-funded by the European Union (Programme ERASMUS2027, ERASMUS-EDU-2021-PEX-EMJM-MOB, Project number 101050809).

## Changelog

Updates to this document will be described here.

### 0.1.0 (2025-06)

Initial version.

## Credits and licensing

Copyright (c) 2025 Diogo Torres, Pedro Lourenço (NOVA University Lisbon). All rights reserved.

This program is licensed under the GNU General Public License (version 3.0).

**Authors**

- Diogo Torres <<dm.torres@campus.fct.unl.pt>>
- Pedro Lourenço <<pedro.lourenco.4816@gmail.com>>
