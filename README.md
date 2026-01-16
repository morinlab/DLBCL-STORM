# DLBCL-STORM Hybrid Capture Panel

Files associated with the DLBCL-STORM (Somatic Tracking Of Residual Mutations) hybrid capture panel. The panel
was created to detect mutations in cfDNA from DLBCL patients and track those variants accross mutliple timepoints
to assess response to treatment.

The full panel is over 618 kb of total target space covering the coding space of 195 genes and 61 non-coding
targets subject to aSHM.

For an example bioinformatics pipeline used to analyse data captured by this panel see:
https://github.com/LCR-BCCRC/lcr-modules/tree/cfdna_pipeline/modules/cfdna_pipeline/1.0

## Bed files

| File | Description |
|------|-------------|
| **DLBCL_STORM_FullPanel_Jan2025.bed** | Full panel with coding and non-coding targets |
| **DLBCL_STORM_aSHM_Jan2025.bed** | aSHM (non-coding) targets |
| **DLBCL_STORM_exons_Jan2025.bed** | Coding targets |

## background mutation rates

| File | Description |
|------|-------------|
| **STORM_background_mutation_rates_JAN2026.tsv* | Index of genomic positions and the point and indel mutation rates and SD generated using the lcr-module artifact_alert, an a panel of over 300 buffy coat samples from DLBCL patients |

## Hotspots

| File | Description |
|------|-------------|
| **mutation_Hotspots_hg38_June2025.txt** | Custom DLBCL hotspot manifest based on data from the GAMBL project |
| **lymphopedia_DLBCL_hotspots_hg38_2026-01-02.vcf.gz** | Hotspot manifest generated using samples from the GAMBL repository (reference in prep) |

GAMBL: https://github.com/morinlab/GAMBLR

## Notspots

| File | Description |
|------|-------------|
| **mutation_Notspots_hg38_June2025.txt** | Custom DLBCL notspot manifest (aka blacklist) based on data from the GAMBL project |
| **technical_artifact_notspots.vcf** | A .vcf of positions that were commonly mutated in a large panel of normals sequenced using DLBCL-STORM. |