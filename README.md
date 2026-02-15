# BRSP-Week2-DEG
# Differential Expression Analysis (Week 2) — GEO2R

## Overview
Repository ini berisi hasil analisis Differentially Expressed Genes (DEG) menggunakan GEO2R.

Analisis dilakukan untuk meninjau sel epitel kelenjar meibomian antara DHT Treated dan Vehicle Treated (kontrol).

---

## Dataset Information
- GEO Accession: GSE18091
- Title: 	Dihydrotestosterone induced changes in gene expression in immortalized human meibomian gland epithelial cells
- Organism: Homo sapiens
- Comparison:
  - Group 1: DHT Treated  
  - Group 2: Vehicle Treated  

---

## Methods (GEO2R Parameters)
Analisis DEG dilakukan menggunakan GEO2R dengan parameter utama:

- Multiple testing correction: Benjamini & Hochberg False Discovery Rate (FDR)
- Significance criteria:
  - Adjusted p-value (adj.P.Val) < 0.05
  - |log2 Fold Change (logFC)| > 1

Replikasi analisis dilakukan sebanyak 3 kali untuk memastikan konsistensi hasil.

---

## Repository Structure

- `data/`  
  Berisi output mentah hasil GEO2R (top table sebelum filtering)

- `results/`  
  Berisi daftar gen signifikan (filtered DEG) berdasarkan kriteria adj.P.Val dan logFC

- `report/`  
  Berisi laporan akhir tugas dalam format PDF

---

## Key Findings (Summary)
Analisis DEG menunjukkan bahwa gen-gen yang terkait dengan proliferasi meningkat ekspresinya (up-regulated) serta gen-gen inhibitor pembelahan menurun ekspresinya (down-regulated). 

