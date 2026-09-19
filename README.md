# Trivalent Triterpenoids MD Data

This repository contains molecular dynamics simulation input files, topology files, structural files, and analysis results supporting the study:

**“Trivalent triterpenoids block SARS-CoV-2 and influenza A virus infection by directly targeting homotrimeric envelope proteins.”**

## Repository Structure

The molecular dynamics simulation data are organized into four systems:

```text
Trivalent-Triterpenoids-MD-Data/
├── 6vxx/
├── 6vxx_18d/
├── 3LZG/
├── 3LZG_protein/
├── .gitignore
└── README.md
```

### Systems

* **6vxx**
  Molecular dynamics simulation system based on PDB ID **6VXX**.

* **6vxx_18d**
  Molecular dynamics simulation system based on PDB ID **6VXX** containing compound **18d**.

* **3LZG**
  Molecular dynamics simulation system based on PDB ID **3LZG** with the corresponding ligand.

* **3LZG_protein**
  Apo protein molecular dynamics simulation system based on PDB ID **3LZG**.

## Included Files

The repository contains the key files required to document and reproduce the molecular dynamics simulations, including:

* `.mdp` — GROMACS molecular dynamics parameter files
* `.top` — system topology files
* `.itp` — molecular topology and force-field parameter files
* `.tpr` — GROMACS portable binary run-input files
* `.gro` — molecular structure files
* `.pdb` — representative molecular structures
* `.ndx` — GROMACS index files
* `.xvg` — GROMACS analysis output
* `.dat` — additional simulation or analysis data
* `.csv` — processed analysis data
* `.mol2`, `.prm`, `.rtp`, `.atp` — ligand or force-field parameter files where applicable

## Trajectory Files

Large molecular dynamics trajectory files such as `.xtc` and `.trr` are not included in the current GitHub repository because of repository file-size limitations.

Representative structures, simulation parameters, topology files, and analysis results are provided to document the simulation setup and downstream analyses.

Trajectory files can be archived separately in an appropriate research-data repository if required.

## Molecular Dynamics Software

The simulations were performed using **GROMACS**.

Detailed simulation parameters for energy minimization, equilibration, and production molecular dynamics are provided in the corresponding `.mdp` files.

## Data Availability

These files are provided as supporting computational data for the associated manuscript and for research-data verification purposes.

## Citation

If you use these data, please cite the associated publication:

**Trivalent triterpenoids block SARS-CoV-2 and influenza A virus infection by directly targeting homotrimeric envelope proteins.**

Full bibliographic information will be added after publication.
