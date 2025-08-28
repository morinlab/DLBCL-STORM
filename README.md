# DLBCL-STORM Hybrid Capture Panel

Files associated with the DLBCL-STORM (Somatic Tracking Of Residual Mutations) hybrid capture panel. 

The full panel is over 618 kb of total target space.

## Bed files

| File | Description |
|------|-------------|
| **DLBCL_STORM_FullPanel_Jan2025.bed** | Full panel with coding and non-coding targets |
| **DLBCL_STORM_aSHM_Jan2025.bed** | aSHM (non-coding) targets |
| **DLBCL_STORM_exons_Jan2025.bed** | Coding targets |

## Hotspots

| File | Description |
|------|-------------|
| **mutation_Hotspots_hg38_June2025.txt** | Custom DLBCL hotspot manifest based on data from the GAMBL project |

GAMBL: https://github.com/morinlab/GAMBLR

## Notspots

| File | Description |
|------|-------------|
| **mutation_Notspots_hg38_June2025.txt** | Custom DLBCL notspot manifest (aka blacklist) based on data from the GAMBL project |
| **technical_artifact_notspots.vcf** | A .vcf of positions that were commonly mutated in a large panel of normals sequenced using DLBCL-STORM. |