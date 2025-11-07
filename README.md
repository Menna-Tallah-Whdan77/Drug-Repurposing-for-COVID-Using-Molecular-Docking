# Drug Repurposing for COVID-19 Using Molecular Docking

A computational drug discovery project focused on identifying FDA-approved drugs with potential efficacy against SARS-CoV-2 through molecular docking studies targeting the COVID-19 main protease (Mpro).

![Computational Biology](https://img.shields.io/badge/Computational-Drug%20Discovery-blue) ![Bioinformatics](https://img.shields.io/badge/Bioinformatics-Molecular%20Docking-green) ![COVID-19](https://img.shields.io/badge/Research-COVID--19-red)

## 📖 Project Overview

This project employs computational drug discovery techniques to identify potential COVID-19 therapeutics through drug repurposing. Using molecular docking approaches, we screened existing drugs against the SARS-CoV-2 main protease (6LU7) to find candidates with strong binding affinity that could inhibit viral replication.

## 🎯 Objectives

- Identify FDA-approved drugs with potential anti-COVID-19 activity
- Evaluate binding affinities of candidate drugs against SARS-CoV-2 main protease
- Analyze protein-ligand interactions to understand inhibition mechanisms
- Expedite therapeutic discovery through computational repurposing

## 🛠️ Tools & Technologies

- **PyRx** - Virtual screening and molecular docking
- **AutoDock Vina** - Docking engine integrated with PyRx
- **Biovia Discovery Studio** - Molecular visualization and interaction analysis
- **ChemDraw** - Chemical structure drawing and preparation
- **PDB Database** - Protein structure retrieval (6LU7 - SARS-CoV-2 Mpro)

## 🔬 Methodology

### 1. Target Preparation
- Retrieved SARS-CoV-2 main protease crystal structure (PDB ID: 6LU7)
- Prepared receptor by removing water molecules and adding hydrogen atoms
- Identified active site with catalytic dyad (Cys145-His41)

### 2. Ligand Preparation
- Curated library of FDA-approved drugs and natural compounds
- Energy minimization and structure optimization
- Format conversion for docking compatibility

### 3. Molecular Docking
- Defined grid box around active site residues
- Performed virtual screening using AutoDock Vina
- Evaluated binding poses and affinities

### 4. Interaction Analysis
- Visualized protein-ligand interactions in 2D and 3D
- Analyzed hydrogen bonding, hydrophobic interactions, and binding stability

## 🧪 Key Experiments

### SARS-CoV-2 Main Protease (6LU7) Analysis
- **Active Site Characterization**: Catalytic dyad Cys145-His41
- **Reference Inhibitor**: N3 inhibitor binding interactions
- **Binding Interactions**: Hydrogen bonds and hydrophobic interactions stabilizing inhibitor binding

### Aloe-emodin Investigation
- **Ligand Preparation**: Energy minimization and model selection
- **Docking Analysis**: Binding pose evaluation and affinity calculation
- **Interaction Mapping**: 2D and 3D visualization of protein-ligand interactions

## 📊 Results & Findings

The project successfully identified several promising drug candidates with strong binding affinities to the SARS-CoV-2 main protease. Key findings include:

- Identification of drugs with potential to inhibit viral replication
- Detailed analysis of Aloe-emodin interactions with Mpro
- Comparison of binding modes with reference inhibitor N3
- Prioritization of candidates for further experimental validation


## 🚀 Getting Started

### Prerequisites
- PyRx software with AutoDock Vina
- Biovia Discovery Studio Visualizer
- ChemDraw or similar chemical drawing tool

### Basic Workflow
1. **Prepare Receptor**: Load and prepare 6LU7 structure in PyRx
2. **Prepare Ligands**: Energy minimization and format conversion
3. **Define Grid Box**: Set coordinates around active site
4. **Run Docking**: Execute virtual screening
5. **Analyze Results**: Visualize and interpret binding interactions

## 💡 Key Features

- **Virtual Screening Pipeline**: Automated docking of compound libraries
- **Interaction Analysis**: Detailed 2D/3D visualization of binding modes
- **Drug Repurposing Focus**: Prioritization of FDA-approved candidates
- **Computational Efficiency**: Rapid screening compared to wet-lab methods


## 🔗 References

1. **Kumar, D., Chandel, V., Raj, S., & Rathi, B. (2020).** *In silico identification of potent FDA approved drugs against Coronavirus COVID-19 main protease: A drug repurposing approach.* Chemical Biology Letters, 7(3), 166-175.

2. **Dallakyan, S., & Olson, A. J. (2015).** *Small-molecule library screening by docking with PyRx.* Chemical biology: methods and protocols, 243-250.

3. Jin, Z., et al. (2020). Structure of Mpro from SARS-CoV-2 and discovery of its inhibitors. Nature

4. Trott, O., & Olson, A. J. (2010). AutoDock Vina: improving the speed and accuracy of docking. Journal of Computational Chemistry

5. PDB ID: 6LU7 - SARS-CoV-2 main protease with N3 inhibitor




*Note: This computational study provides preliminary evidence for drug repurposing candidates. Experimental validation is required for clinical applications.*
