## Datasets & Data Artifacts

The core datasets supporting this study are included in this repository. The primary corpus is sourced from the open-access OpenAlex API.

| Dataset Name | File Name | Description |
| :--- | :--- | :--- |
| **Longitudinal Scientific Corpus (2016–2026)** | `raw_papers.parquet` | Raw corpus of 54,521 scholarly publications collected via OpenAlex, including reconstructed abstracts, citations, author IDs, and affiliations. |
| **9D Multimodal Spatiotemporal Features & APFT** | `spatiotemporal_features.parquet` | Processed annual topic-state feature matrices containing publication volumes, citations, semantic novelty drift, structural connectivity, precursor influx, and EWEI scores. |
| **Prospective 2027 Scientific Foresight Leaderboard** | `future_topic_forecasts.csv` | The model's out-of-sample forward projections across all 39 topic clusters for the 2027 horizon, detailing baseline volumes, phase accelerations, and Future Priority Scores. |
