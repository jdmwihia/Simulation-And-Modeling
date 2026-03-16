# Simulation & Modeling Projects

## Description
This repository contains all **Simulation & Modeling projects** for the semester.  
Each project applies simulation techniques to explore real-world scenarios, analyze outcomes, and visualize results using Python.

The first project, `diceRoller.ipynb`, simulates rolling dice multiple times, calculates probabilities, and displays the results in a table. Future projects will expand on simulation concepts, probability analysis, and modeling scenarios.

---

## Repository Structure
```bash
Simulation-And-Modeling/
├── .gitignore # ignores project virtual env
├── diceRoller.ipynb # First project: dice rolling simulator
├── requirements.txt # Python dependencies used across projects
└── README.md # This file
```

---

## How to Run a Project

1. **Clone the repository**:
```bash
git clone https://github.com/jdmwihia/Simulation-And-Modeling.git
```

2. **Navigate to the project folder**:
```bash
cd "Simulation-And-Modeling"
```

3. **Create and activate the virtual environment**:
```bash
python3 -m venv Sim-venv
source Sim-venv/bin/activate
```

4. **Install dependencies**:
```bash
pip install -r requirements.txt
```

5. **Open and run the Jupyter notebook for the desired project**:
```bash
jupyter notebook diceRoller.ipynb
```