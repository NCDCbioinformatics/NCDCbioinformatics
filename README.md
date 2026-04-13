<p align="center">
  <img src="assets/profile-hero.svg" alt="NCDCbioinformatics profile banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/NCDCbioinformatics/cure-ngs-panel-harmonization-framework"><img alt="Umbrella Repository" src="https://img.shields.io/badge/Umbrella-CURE--NGS_Framework-0f766e.svg"></a>
  <a href="https://www.cancerdata.re.kr/"><img alt="National Cancer Data Center" src="https://img.shields.io/badge/NCDC-National_Cancer_Data_Center-1d4ed8.svg"></a>
  <img alt="Location" src="https://img.shields.io/badge/Location-Goyang,_Republic_of_Korea-334155.svg">
</p>

## About

`NCDCbioinformatics` is the public bioinformatics profile of the National Cancer Data Center, focused on reproducible research software for precision oncology and multi-institutional panel NGS harmonization.

Current public work includes:

- VCF harmonization and MAF-centered processing pipelines
- HGVS normalization and HGVS-to-MAF conversion workflows
- Gene and fusion nomenclature standardization utilities
- Publication-facing framework documentation for CURE-NGS
- Related clinico-omics portal and synthetic-data showcase projects

## Featured Project

> The main publication-facing entry point is the [CURE-NGS panel harmonization framework](https://github.com/NCDCbioinformatics/cure-ngs-panel-harmonization-framework), which consolidates manuscript metadata, declarations, software inventory, and links to component repositories.

## Public Repositories

| Repository | Purpose |
| --- | --- |
| [cure-ngs-panel-harmonization-framework](https://github.com/NCDCbioinformatics/cure-ngs-panel-harmonization-framework) | Umbrella repository for the manuscript and editorial metadata |
| [panel_VCF_vcf2maf_pipeline](https://github.com/NCDCbioinformatics/panel_VCF_vcf2maf_pipeline) | Multi-panel VCF preprocessing, build harmonization, and VCF-to-MAF conversion |
| [HGVS_to_minimal_MAF_pipeline](https://github.com/NCDCbioinformatics/HGVS_to_minimal_MAF_pipeline) | HGVS-driven minimal MAF generation pipeline |
| [minimal_MAF_to_annotated_MAF_pipeline](https://github.com/NCDCbioinformatics/minimal_MAF_to_annotated_MAF_pipeline) | Minimal-MAF-to-annotated-MAF conversion pipeline |
| [gene_name_harmonization](https://github.com/NCDCbioinformatics/gene_name_harmonization) | Gene symbol harmonization utility |
| [gene_fusion_normalizer](https://github.com/NCDCbioinformatics/gene_fusion_normalizer) | Fusion gene normalization utility |
| [hgvs_normerlizer](https://github.com/NCDCbioinformatics/hgvs_normerlizer) | HGVS nomenclature normalization utility |

## K-CORE Portal Repositories

The broader NCDC public software ecosystem also includes separately maintained K-CORE portal repositories covering full-stack web services, visualization, and synthetic demonstration datasets.

| Project | Area | Summary |
| --- | --- | --- |
| [K-CORE profile](https://github.com/K-CORE-NCDC) | Portal overview | Public K-CORE analytic portal profile maintained separately from this account |
| [ncc-backend](https://github.com/K-CORE-NCDC/ncc-backend) | Backend platform | Django and Django REST backend for the K-CORE clinico-omics portal with PostgreSQL and SQLite workflows |
| [ncc-frontend](https://github.com/K-CORE-NCDC/ncc-frontend) | Frontend visualization | React-based portal UI for clinico-omics exploration and precision oncology visual analytics |
| [synthetic-data-set](https://github.com/K-CORE-NCDC/synthetic-data-set) | Demonstration data | Synthetic omics-oriented dataset package used for portal validation and demonstration |

These K-CORE repositories remain in their original source profile and are referenced here without modifying the original `K-CORE-NCDC` account.

## Focus Areas

- Harmonization of heterogeneous clinical panel NGS outputs
- Provenance-aware transformation of VCF, HGVS, and report-derived inputs
- Research-ready mutation annotation workflows
- Terminology normalization for cancer genomics data integration
- Full-stack clinico-omics platform engineering and data visualization

## Contact

- Institution: National Cancer Data Center
- Website: [www.cancerdata.re.kr](https://www.cancerdata.re.kr/)
- Location: Goyang-si, Gyeonggi-do, Republic of Korea

## Notes

The repositories under this profile are intended for research software and framework documentation. Patient-level clinical or genomic data are not distributed through this profile.
