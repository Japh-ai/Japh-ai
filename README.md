# Jorge Puente

**Machine learning researcher building deep learning for earthquake science and LLM agent systems.**

I'm a Ph.D. candidate in Seismology & Machine Learning at Charles University and a researcher at the Institute of Geophysics of the Czech Academy of Sciences. I build deep learning systems in PyTorch (Transformers, CNNs, RNNs) for large multivariate time-series data, from raw-data pipelines to evaluation, trained on GPUs on HPC clusters. A lot of my work is benchmarking: comparing models on precision, recall, F1, AUC, probabilistic scores and runtime. I apply the same approach to LLM systems.

Prague, Czech Republic · Open to machine learning, deep learning, AI engineering and seismology research roles · [LinkedIn](https://linkedin.com/in/jorgepuente)

## Projects

| Project | What it does | Stack |
|---|---|---|
| **[Job Skill Gap Agent](https://github.com/Japh-ai/job-skill-gap-agent)** | Pulls job posts through an MCP server, extracts them into validated Pydantic records in SQLite, and compares the most requested skills with what I've built. Fixed workflows plus a LangChain agent with 6 tools across two MCP servers and local SQL. | LangChain · MCP · Pydantic · SQLite · Ollama |
| **[TEAM_pytorch](https://github.com/Japh-ai/TEAM_pytorch)**<br>[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22143669.svg)](https://doi.org/10.5281/zenodo.22143669) | Reimplemented and extended a multi-station Transformer for real-time probabilistic peak ground acceleration estimation (earthquake early warning), from TensorFlow to PyTorch, with mixture-density outputs and configurable training and evaluation. | PyTorch · Transformers · HPC / GPU |
| **[Chile strong-motion dataset](https://doi.org/10.5281/zenodo.22072434)**<br>[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22072434.svg)](https://doi.org/10.5281/zenodo.22072434) | ML-ready dataset I built and published: 407,631 station-event records of 55,651 earthquakes (M1.0–M8.2) from 88 stations in Chile, 2007–2020, with analyst-reviewed P-wave picks and ground-motion labels. | HDF5 (28.9 GB) · data pipelines |
| **[Seismic phase association benchmark](https://doi.org/10.26443/seismica.v4i2.1559)** | Benchmark of five phase associators, from classical algorithms to GNN- and RNN-based models, on synthetic scenarios with known ground truth. Stress-tested on event density, false detections, missing data, timing noise and out-of-network events. First-author paper in *Seismica* (2025). | Python · GNNs · RNNs · HPC |
| **[CNN-based-Earthquake-detector](https://github.com/Japh-ai/CNN-based-Earthquake-detector)** | 1D CNN pipeline that detects earthquakes in 3-component seismic waveforms. | Python · CNNs |
| **[HPC-chatbot-nltk](https://github.com/Japh-ai/HPC-chatbot-nltk)** | Rule-based chatbot answering SSH, SLURM and module questions for university HPC cluster users. | Python · NLTK |

## Tech

- **LLM systems:** LangChain · LangGraph · MCP · Ollama · RAG · embeddings · Chroma · Pydantic structured outputs · tool calling · Claude Code
- **ML / DL:** PyTorch · Transformers · CNNs · RNNs · transfer learning · probabilistic modelling · model evaluation
- **Data and infra:** Python · SQL · SQLite · NumPy · pandas · HDF5 · Hydra · Linux · Slurm / HPC · GPU training · Git

## Publications

- **Puente Huerta, J. A.**, Sippl, C., Münchmeyer, J., & McBrearty, I. W. (2025). *Benchmarking seismic phase associators: Insights from synthetic scenarios.* Seismica, 4(2). https://doi.org/10.26443/seismica.v4i2.1559
- Riedel-Hornig, M., Sippl, C., Tassara, A., Ruiz, S., Potin, B., **Puente Huerta, J. A.** (2026). *Seismicity catalogue of the entire Chilean margin (18°–56°S) from an automated approach.* Earth System Science Data.
- **Puente Huerta, J. A.**, González-Escobar, M., & Stock, J. M. (2022). *Structure of the Northern Altar Pull-Apart Basin revealed by a 2D reflection seismic survey.* Pure and Applied Geophysics, 179(9), 3191–3216. https://doi.org/10.1007/s00024-022-03138-1

**Dataset and software**

- **Puente Huerta, J. A.**, Sippl, C., & Münchmeyer, J. (2026). *A machine-learning-ready strong-motion dataset for earthquake early warning in Chile (2007–2020)* [Data set]. Zenodo. https://doi.org/10.5281/zenodo.22072434
- **Puente Huerta, J. A.**, Sippl, C., & Münchmeyer, J. (2026). *A PyTorch reimplementation of the Transformer Earthquake Alerting Model (TEAM)* [Software]. Zenodo. https://doi.org/10.5281/zenodo.22143669
- Sippl, C., Luhta, T., Penttinen, M., Godova, D., **Puente Huerta, J. A.**, & Kamm, J. (2025). *UNDERCOVER Broadband Array Finland* [Data set]. GFZ Data Services. https://doi.org/10.14470/1U581562

## Talks

- Poster, EGU General Assembly, Vienna (2025): *Toward a multi-station deep learning framework for enhanced earthquake early warning.*
- Oral, AGU Annual Meeting, Washington DC (2024): *Turning picks into events: Evaluating seismic phase associators across ML models under synthetic noise conditions.*
- Poster, Chilean Geological Congress (2023): *Improving Northern Chile's earthquake catalog: comparative analysis of ML phase associators.*
- Orals, EGU General Assembly, Vienna (2022, 2023): benchmarking and performance evaluation of ML phase association algorithms.
- Seminar, Charles University, Prague (2022): machine learning for seismic phase picking and association.

## Recent training

- Agentic Earth Observation Workshop: LLM agents & AI for science, Berlin (2026)
- Practical Deep Learning on HPC: CSC / LUMI supercomputer, Finland (2025)
- AI & Machine Learning for Geosciences: Barcelona Supercomputing Center, Spain (2024)
