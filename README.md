# lean-service-optimization
Python scripts for analyzing automotive service center operations using time study, discrete event simulation, and queueing theory. Based on 205 real‑world vehicle observations from a Jiffy Lube location. Includes simulation model, statistical analysis, and reproduction of thesis figures.
# Lean Service System Optimization – Automotive Service Center Case Study

This repository contains the Python code and data used in the thesis *"A Comprehensive Analysis and Simulation‑Based Optimization of a Lean Service System: A Case Study in Automotive Service"* by Rakibul Hasan Sarker (Minnesota State University, Mankato, April 2026).

The project analyzes service performance at a U.S. automotive service center using real shop‑floor data (205 vehicle observations). The analysis includes statistical hypothesis testing (ANOVA, t‑tests), discrete event simulation (SimPy), queueing theory (M/M/c), and lean waste identification. The scripts reproduce all figures and tables presented in the thesis.

## Repository Contents

| File | Description |
|------|-------------|
| `analysis_simulation.py` | Main script: data loading, descriptive statistics, ANOVA, t‑tests, simulation model, generation of Figures 1–6 and 15 |
| `queueing_theory_validation.py` | M/M/c queueing calculations, correct interarrival time derivation, Little’s Law validation |
| `research_simulation_alignment.py` | Alignment validation, three‑panel Figure 14 (pie charts + stacked bar), cascade effect analysis |
| `service time data.xlsx` | Raw dataset with 205 vehicle records (4 sheets: Service Time, BAY Time, Total Process Time, NON Value Added) |
| `requirements.txt` | Python package dependencies |

## Prerequisites

- Python 3.10 or higher
- The required packages are listed in `requirements.txt`. Install them with:

```bash
pip install -r requirements.txt
