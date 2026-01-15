---
layout: about
title: about
permalink: /
subtitle: Division of Artificial Intelligence Engineering, <a href='https://www.sookmyung.ac.kr'>Sookmyung Women's University</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Seonghoon Jeong</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

## Welcome to SNSec Lab
SNSec Lab. investigates and addresses cybersecurity challenges in Internet service applications through a data-driven approach that utilizes machine learning and deep learning methodologies. Our team analyzes massive live data streams to secure computer systems and networks from evolving threats, leveraging experience with diverse datasets including commercial server-side logs, root DNS servers, mobile payment transactions, and car hacking activities.

We specialize in identifying and explaining intrusions in connected vehicles, notably employing anomaly detection techniques trained solely on benign data.

### Key Research Areas

*   **Trustworthy Network Intrusion Detection:** We aim to move beyond simple classification accuracy to build systems that are robust, adaptive, and explainable using Foundation Models.
    *   **Multi-modal Traffic Representation & Pre-training:** Integrating payload bytes, packet sequences, and protocol metadata to learn comprehensive traffic representations without information loss.
    *   **Drift Resilience & Efficient Adaptation:** Developing unsupervised metrics to detect concept drift in real-time and utilizing parameter-efficient fine-tuning (PEFT) to adapt models to new environments with minimal cost.
    *   **Generative & Causal Reasoning:** Applying generative AI to not only detect threats but also explain their causes (causal reasoning) and suggest response scenarios.

*   **Automotive Security:** We are developing an **Explainable Unsupervised IDS for Automotive Ethernet** and researching standardized intrusion prevention systems for connected vehicles to offer practical solutions for both industry and academia.

*   **Advanced Threat Detection:** We are developing **DRIFT (Drift-Resilient Invariant-Feature Transformer)**, an advanced DGA detector that uses a hybrid tokenization strategy and multi-task self-supervised pre-training to maintain robustness against evolving domain generation algorithms.

*   **AI-driven Proactive Resilience:** We engineer autonomous solutions that transform reactive defense into proactive resilience by bridging the gap between deep system telemetry (Linux, Windows, macOS) and multi-modal Foundation Models. Our goal is to automate the real-time situational assessment of live systems and identify potential cybersecurity issues before they escalate. [Read more about our research vision here.]({{ '/blog/2026/vision-cybersecurity-ai/' | relative_url }})

{% include figure.liquid path="assets/img/about_research.png" class="img-fluid z-depth-1 rounded" %}

## Research and collaborations in progress

*   Bi-modal *Enhanced* Explainable IDS for Controller Area Network (with Dr. Hyunjae Kang)
*   Explainable IDS for Automotive Ethernet (with Jisoo Kim)
*   *Drift-Resilient* robust DGA domain name detection (with Chaeyoung Lee and Chaeri Jung)
*   Meta-learning based few-shot IDS for IoT devices (with the University of Queensland)
*   J1939 based IDS for connected vehicles (with Korea University)
*   Robustifying DeepFake Detection against adversarial perturbations (with the University of Queensland)
*   Vulnerability Assessment for ISO 15765-2 (with Korea University)