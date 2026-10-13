# Bilateral Trade Discrepancy Research

Research artifacts for comparing the coverage and consistency of international trade datasets, alongside visualizations from trade-network analysis.

This work relates to my software-development research at the University of Cincinnati, where I build Python data workflows for cross-national trade analysis and network measures.

## Research focus

- Compare dataset time spans, recorded entities, and import/export observations.
- Examine missing values and zero-valued trade records.
- Distinguish country coverage from coverage that also includes other reporting entities.
- Explore network-centrality measures across trade data.

## Repository guide

| File | Purpose |
| --- | --- |
| [Data Table.docx](Data%20Table.docx) | Working comparison table and data-quality notes across nine sources. |
| [NA_counts_plot.pdf](NA_counts_plot.pdf) | Missing-value count visualization. |
| [country_counts_plot.pdf](country_counts_plot.pdf) | Recorded-country/entity coverage visualization. |
| [country_counts_plot_NA.pdf](country_counts_plot_NA.pdf) | Companion coverage visualization addressing missing values. |
| [eigen0.png](eigen0.png) | Network-analysis figure. |
| [weighted_directed_degree_normalized.png](weighted_directed_degree_normalized.png) | Normalized weighted directed-degree figure. |

## Sources compared

The working table covers COW, Gleditsch, IMF, CEPII, NBER, UN Comtrade, WTO, OECD, and Eurostat.

Coverage is not directly interchangeable across sources. The notes flag differences in treatment of missing values, zero records, and entities that are not individual countries. Those choices matter when comparing dataset sizes or interpreting network results.

## View the results

Start with the Word table for context, then open the PDFs and images.

![Normalized weighted directed degree](weighted_directed_degree_normalized.png)

## Reproducibility

This repository currently contains research outputs and working notes. The underlying datasets, transformation scripts, and network-analysis code are not included. Reproducing the figures requires those inputs and their source-specific cleaning rules.

The wider research workflow uses Python tools for data processing and network analysis; the artifacts here should not be read as a packaged or independently runnable pipeline.
