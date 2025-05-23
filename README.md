
# LLM-MultiModal-for-DSSE

Official implementation for the manuscript submitted to **CSEE JPES**,  
**"Enhancing Distribution System State Estimation Under Limited Measurements: Leveraging Large Language Model and Multimodal Information"**.

## Project Description

This repository presents research code and data formats for enhancing distribution system state estimation (DSSE) under limited measurements. The proposed approach leverages large language models (LLMs) and multimodal data to achieve improved state estimation accuracy.

## Repository Structure

```
/
├── data/
│   ├── p_ij_rtm
│   ├── q_ij_rtm
│   ├── PQ_input_data
│   ├── line_input_data
│   ├── prompt.json
│   └── v_m_labels
├── 1-MV-urban--0-sw_v.ipynb
├── README.md
└── ...
```

## Data Description

The `/data/` directory contains sample data formats used by the provided code:

- **p_ij_rtm**: Real-time active power measurements on lines.
- **q_ij_rtm**: Real-time reactive power measurements on lines.
- **PQ_input_data**: Active and reactive power values at all nodes.
- **line_input_data**: Concatenated line power data.
- **prompt.json**: Text-based prompts and descriptions for modeling.
- **v_m_labels**: Ground-truth labels for state estimation results.

## Getting Started

The code is primarily organized in the notebook:

- **1-MV-urban--0-sw_v.ipynb**:  
  Main notebook detailing the model, experimental setup, and analysis.  
  Open this file to access the complete methodology and results as described in the paper.

## Citation

If you find this repository helpful or use it in your research, please cite our manuscript:

> Enhancing Distribution System State Estimation Under Limited Measurements: Leveraging Large Language Model and Multimodal Information  
> (Submitted to CSEE JPES)

---

Thank you for your interest!
