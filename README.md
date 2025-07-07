# VQE H₂ Molecule Analysis

Interactive Variational Quantum Eigensolver implementation for calculating the ground state energy of hydrogen molecule using quantum computing principles.

## Project Overview
This project demonstrates the practical application of quantum computing to quantum chemistry by implementing a Variational Quantum Eigensolver (VQE) to find the ground state energy of the H₂ molecule at equilibrium bond distance.

## Key Results
- **Ground State Energy**: -1.136189 Hartree (achieved chemical accuracy)
- **Error from Classical**: < 1.6 mHartree (chemical accuracy threshold)
- **Optimisation Convergence**: 30 steps
- **Method**: 4-qubit VQE with parameterized ansatz

## Notebooks
1. **`01_H2_Hamiltonian.ipynb`** - Interactive H₂ molecule exploration with bond distance slider
2. **`02_VQE_Implementation.ipynb`** - VQE algorithm implementation with real-time parameter adjustment
3. **`03_VQE_Optimisation.ipynb`** - Optimisation visualisation and convergence analysis  
4. **`04_Results_Dashboard.ipynb`** - Comprehensive results dashboard and professional presentation

## Technologies Used
- **Python**: NumPy, SciPy, Matplotlib
- **Jupyter Lab**: Interactive notebooks with widgets
- **Quantum Computing**: VQE algorithm simulation
- **Quantum Chemistry**: Molecular Hamiltonian, STO-3G basis set

## Features
- **Interactive Widgets**: Real-time parameter adjustment and energy calculation
- **Professional Visualizations**: Multi-panel analysis dashboard
- **Educational Content**: Step-by-step explanation of quantum chemistry concepts
- **Reproducible Results**: Complete analysis pipeline from theory to results

## Skills Demonstrated
- Quantum algorithm implementation (VQE)
- Interactive scientific computing and visualization
- Optimisation and numerical methods
- Bridge between quantum chemistry and quantum computing
- Professional scientific communication and presentation

## Usage
1. Clone this repository
2. Install dependencies: `pip install numpy scipy matplotlib jupyter ipywidgets`
3. Run `jupyter lab`
4. Open notebooks in order and execute cells

## Impact
This implementation showcases practical quantum computing applications in molecular science, demonstrating how near-term quantum algorithms can solve real chemical problems with chemical accuracy.

---
*Built as a portfolio project demonstrating quantum computing skills for quantum chemistry applications.*
