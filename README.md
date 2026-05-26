# VfHub
VfHub is a curated repository of putative bacterial virulence factors predicted by VirulentPred2 (and future tools). It currently includes E. amylovora and will expand to other bacterial pathogens.
# VfHub – v1.0 (VirulentPred2)

## Overview

**VfHub** is a curated repository of **putative bacterial virulence factors** predicted using **VirulentPred2**, a machine‑learning tool for bacterial virulence protein prediction.

The first release (v1.0) includes data from **317 *Erwinia amylovora*** genomes, the causative agent of fire blight. Future versions will expand to other plant, animal, and human pathogens.

### Current contents (v1.0)

Two core FASTA files are provided:
- `predicted_virulent.fasta` – 15,535 sequences predicted as virulence factors (after deduplication, see Methods).
- `non_virulent.fasta` – 141,005 unique hypothetical proteins that VirulentPred2 classified as non‑virulent (useful as negative controls).

## Key Statistics (from the accompanying manuscript)

| Metric | Value |
|--------|-------|
| *E. amylovora* strains | 317 |
| Total hypothetical proteins screened | 321,034 |
| Non‑redundant unique hypotheticals | 141,005 |
| **Final predicted VFs (VirulentPred2)** | **15,535** |
| Negative control sequences | 125,470 (after duplicate removal) |
