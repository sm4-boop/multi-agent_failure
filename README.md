# Multi-Agent LLM Communication Analysis

This project was completed as part of an MSc research project applying network science methodology to understand whether failing multi-agent LLM systems have distinct communication network properties. LLM traces under the HyperAgent framework are examined. 

**Research Aim**
Investigating whether communication network properties differs between successful and failing multi-agent LLM systems.

**Method**  
Modelled agent interactions as networks and analysed their structural characteristics using Python, NetworkX and PyVis.

**Key Finding**  
Identified distinct communication patterns associated with system failure, suggesting network structure may offer potential signals for monitoring multi-agent system reliability.

**Dependencies**
Python >= 3.10

Analysis: pandas, networkx, raphtory, matplotlib

**Accessing LLM Traces** 
The LLM traces used for this analysis are publicly available for download at https://huggingface.co/datasets/mcemri/MAST-Data 

**Acknowledgment**
This project builds on the work of Cemri et al (2025) who examined why multi-agent LLM systems fail and released a publicly available dataset consisting of LLM traces via HuggingFace. These traces are futher explored in this project. 

**Project Structure**
multi-agent-comms-analysis/
├── data
    └── MAD_full_dataset.json
├── graphs
├── notebook
    └── analysis.ipynb
├── .gitignore
├── README.md



