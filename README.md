# Beryllium-7 in classical novae

Reproduction data for *Ionization corrections to ⁷Be abundances in classical novae: New spectroscopy of V1405 Cassiopeiae and a reanalysis of three other novae*.

Download the [base reproduction archive](V1405Cas-7Be-reproduction.zip), the [Fe/H update](V1405Cas-7Be-FeH-update-20261127.zip), and the [fifth-review update](V1405Cas-7Be-referee5-update-20261127.zip). Extract them in that order into the same directory and replace matching files. Start with the resulting manuscript_reproduction/README.md. It indexes 23 manuscript figures, 18 tables, four electronic tables, and three supplementary figures.

**Matching manuscript version.** The 27 November 2026 fifth-review revision adds UV025 synthetic photometry (section 7.1), the Fe II column comparison (Table 14), and the eight Balmer sensitivity runs (Table 18, Appendix 9). The fifth-review update includes source CSVs, calculation scripts, Cloudy C25.00 input decks and selected diagnostic outputs. For the earlier Fe/H and hydrogen-column grids, Figure 23, and the comparison-nova diagnostics, use the Fe/H update.

The supplementary plots can also be viewed directly for [V339 Del](supplementary_figures/V339Del_FeH_NH_diagnostics.pdf), [V5668 Sgr](supplementary_figures/V5668Sgr_FeH_NH_diagnostics.pdf), and [V2944 Oph](supplementary_figures/V2944Oph_FeH_NH_diagnostics.pdf). Their source CSVs and scripts are in `manuscript_reproduction/comparison_nova_feh_nh_sensitivity/` inside the ZIP.

Raw Subaru/HDS frames are available from [SMOKA](https://smoka.nao.ac.jp/). The observation log gives the dates and instrumental settings.

Verify the three downloaded ZIP files against [SHA256SUMS](SHA256SUMS).
