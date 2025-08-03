# Forex Simulation & Impermanent Loss Research

This project contains:
- A LaTeX paper analyzing impermanent loss risk in single-sided liquidity pools for FX markets.
- A simulation notebook that uses real historical FX data (e.g., MYR/USD, SGD/USD).
- Analysis to compare LP performance vs. fixed deposit benchmarks.
- Outputs usable in designing future fee structures for universe.forex.

## How to Run

### 1. Compile the LaTeX Paper
- Go to the `paper/` folder
- Open `main.tex` with any LaTeX editor (TeXShop, Overleaf, VS Code + LaTeX Workshop)
- Compile using `pdflatex main.tex` or your preferred compiler
- Output PDF will be created in the same folder

### 2. Run the Simulation
- Go to the `notebooks/` folder
- Open `simulation_template.ipynb` in Jupyter, Google Colab, or VS Code
- Make sure Python + libraries (`pandas`, `numpy`, `matplotlib`) are installed
- Run all cells to simulate LP results and generate plots

## Folder Structure

forex-simulation-paper/
├── paper/
├── notebooks/
├── figures/
├── data/
├── README.md


## License
Internal research project (not for public reuse without permission).
