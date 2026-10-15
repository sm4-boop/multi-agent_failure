# Multi-Agent LLM Communication Analysis

This MSc research project applies network science to investigate whether failing multi-agent large language model (LLM) systems exhibit distinct communication network properties. LLM traces generated under the HyperAgent framework are analysed.

## Research Aim

Investigate whether communication network properties differ between successful and failing multi-agent LLM systems.

## Method

Agent interactions are modelled as networks and analysed using Python, NetworkX and PyVis.

## Key Finding

Identified distinct communication patterns associated with system failure, suggesting that network structure may provide potential signals for monitoring multi-agent system reliability.

## Dependencies

- Python ≥ 3.10
- pandas
- NetworkX
- Raphtory
- Matplotlib

## Data Access

The LLM traces used in this analysis are publicly available through the [MAST-Data dataset on Hugging Face](https://huggingface.co/datasets/mcemri/MAST-Data).

Download the dataset and place `MAD_full_dataset.json` in the `data/` directory before running the analysis.

## Acknowledgements

This project builds on the work of Cemri et al. (2025), who investigated failure modes in multi-agent LLM systems and released a dataset of LLM traces through Hugging Face. This project extends that work by examining the traces through a network science lens.

## Project Structure

```text
multi-agent-comms-analysis/
├── data/                 # Downloaded dataset (not included)
├── graphs/               # Network graphs and visualisations
├── notebook/
│   └── analysis.ipynb     # Analysis notebook
├── .gitignore
└── README.md
```
