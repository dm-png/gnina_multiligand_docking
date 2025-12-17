# High-Throughput Virtual Screening with GNINA

This repository contains a workflow for performing virtual screening of ligand libraries against the **MAO-B** (Monoamine Oxidase B) receptor using **GNINA**, a deep learning-based molecular docking tool.

## 📂 Repository Structure

- **`vs_gnina.ipynb`**: The main Jupyter Notebook containing the screening pipeline, analysis, and visualization.
- **`ligands/`**: Directory containing the input ligand files (.pdb or .sdf).
- **`MAO_B.pdb`**: The target receptor structure.
- **`SAG.pdb`**: The co-crystallized ligand (used for defining the binding pocket/autobox).
- **`docked_results/`**: (Generated) Output folder for docked poses (.pdbqt).
- **`logs/`**: (Generated) Output folder for docking logs.

## 🚀 Getting Started

### Prerequisites
This workflow is optimized for **Google Colab** (Linux/GPU environment) but can be adapted for local Linux machines.

**Core Dependencies:**
- Python 3.8+
- [GNINA](https://github.com/gnina/gnina) (v1.3+)
- OpenBabel (`sudo apt install openbabel` or `conda install openbabel`)

### Installation
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/gnina_multiligand_docking.git](https://github.com/YOUR_USERNAME/gnina_multiligand_docking.git)
   cd gnina_multiligand_docking
