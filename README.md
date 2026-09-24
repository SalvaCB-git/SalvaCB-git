<p align="center">
  <img src="assets/profile-banner.svg" width="100%" alt="Salvador Cascón Bertomeu — Software and Data Engineer focused on Applied AI and Cyber Threat Intelligence" />
</p>

I build software and data systems that turn messy information into decisions
that can be explained, tested and reproduced. My strongest work sits where
backend engineering, data pipelines, applied AI and defensive security meet.

I completed my Computer Engineering degree in July 2026. During my internship,
I worked with operational data workflows, ETL orchestration and failure
diagnosis. My final-year project became a deployed ransomware intelligence
pipeline rather than a notebook-only prototype.

<table>
  <tr>
    <td width="33%" valign="top">
      <strong>Software &amp; data</strong><br><br>
      Python, SQL, REST APIs, ETL, Airflow, Docker and reproducible workflows.
    </td>
    <td width="33%" valign="top">
      <strong>Applied AI</strong><br><br>
      RAG, local LLMs, structured outputs, evaluation and human calibration.
    </td>
    <td width="33%" valign="top">
      <strong>Cybersecurity</strong><br><br>
      Cyber threat intelligence, MITRE ATT&amp;CK, ransomware research and secure deployment.
    </td>
  </tr>
</table>

## Featured project

### Ransomware Intelligence Pipeline

An end-to-end CTI system that collects public ransomware reporting, maps
evidence to MITRE ATT&amp;CK with a local LLM and retrieval, and validates the
result with an independent model and human calibration.

- Normalizes and deduplicates **3,871 reports from 13 public sources**.
- Reaches **0.726 F1** and **0.577 MCC** on the complete validation pipeline.
- Separates extraction from evaluation and documents the limits of every metric.
- Runs as a split deployment: an always-on service plus a local GPU worker.
- Includes **25 deterministic tests**, **13 statistical reference tests** and a
  production dependency smoke test.

**[Source and reproducibility](https://github.com/SalvaCB-git/ransomware-intelligence-pipeline)**
· **[Live read-only demo](https://scraper.143.47.55.55.sslip.io/demo)**
· **[Architecture](https://github.com/SalvaCB-git/ransomware-intelligence-pipeline#system-overview)**

`Python` `Scrapy` `Flask` `SQLite` `Docker` `RAG` `Local LLMs` `MITRE ATT&CK`

## Current direction

I am extending this work into a broader engineering portfolio and a small
defensive CTI lab. The goal is to connect research outputs with practical
artifacts such as structured intelligence and detection content, while keeping
the evaluation reproducible.

I am open to graduate and junior opportunities in backend engineering, data
engineering, security automation, cyber threat intelligence and applied AI.

**EU citizen · Based in southern Spain · Open to relocation across Europe · English C1**
