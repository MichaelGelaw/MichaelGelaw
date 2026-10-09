<div align="center">

# Hi, I'm Michael Gelaw 👋

[![Portfolio](https://img.shields.io/badge/Portfolio-michaelgelaw.github.io-b7ff3f?style=for-the-badge&logo=google-chrome&logoColor=070a09)](https://michaelgelaw.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-MichaelGelaw-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/MichaelGelaw)
[![Resume](https://img.shields.io/badge/Resume-PDF_Download-5eead4?style=for-the-badge&logo=adobe-acrobat-reader&logoColor=070a09)](https://michaelgelaw.github.io/Michael-Gelaw-CV.pdf)
[![Email](https://img.shields.io/badge/Email-michaeldessie96%40gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:michaeldessie96@gmail.com)

<p align="center">
  <b>Computer Engineering Student (GPA: 3.97 / 4.0) @ University of Dubai</b><br />
  <i>Systems Programming • Multimodal Machine Learning • Distributed Architecture • Edge IoT</i><br />
  📍 Dubai, United Arab Emirates
</p>

---

</div>

## 📌 About Me

I am a Computer Engineering student passionate about the intersection of **low-level systems, machine learning pipelines, and real-time edge computing**. I focus on building scalable, reliable, and rigorously tested software—from concurrent C11 memory allocators to multi-modal vision-language models and edge IoT digital twins.

- 🎓 **Education:** B.S. in Computer Engineering at **University of Dubai** (2023 – Present) | **GPA: 3.97 / 4.0**
- 🔬 **Current Research:** Real-time occupancy tracking on **NVIDIA Jetson Orin Nano**, integrating Matter/ESP32 smart spaces and local LLMs (**Ollama**).
- 🏆 **Academic Honors:** Dean's Honor List (2025) · MathWorks Certified in ML · Huawei ICT Academy Python.
- 🚣 **Activities:** 3rd Place at the **Abu Dhabi Dragon Boat Festival** (2025) · IEEE ICCE 2026 Volunteer · 19th IEEE UAE Student Day.

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/MichaelGelaw/TruLens">🔍 TruLens</a></h3>
      <p><b>Multimodal "Cheapfake" Misinformation Detector</b></p>
      <ul>
        <li>Fuses visual semantic features from <b>CLIP</b> with text embeddings from <b>DeBERTa-v3</b> via a custom <b>Gated Multimodal Unit (GMU)</b>.</li>
        <li>Achieved <b>0.858 AUROC</b> (+12.3% accuracy over unimodal baselines).</li>
        <li>Integrated Captum/Grad-CAM explainability, mixed-precision training, and a <b>75-test Pytest suite</b>.</li>
      </ul>
      <p><b>Tech:</b> <code>PyTorch</code> <code>CLIP</code> <code>DeBERTa-v3</code> <code>Captum</code> <code>Gradio</code> <code>Pytest</code></p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/MichaelGelaw/mini-ci">⚡ Mini-CI</a></h3>
      <p><b>Distributed CI/CD Platform with DAG Execution</b></p>
      <ul>
        <li>Distributed pipeline engine with multi-job DAG scheduling, sandboxed Docker/shell runners, and HMAC-SHA256 authenticated webhooks.</li>
        <li>Implemented reliable queue consumers, <b>lease-token fencing</b>, dead-worker detection, and <b>Server-Sent Events (SSE)</b> log streaming.</li>
        <li>Validated fault-tolerance through chaos and high-concurrency load testing.</li>
      </ul>
      <p><b>Tech:</b> <code>Distributed Systems</code> <code>Docker</code> <code>SSE</code> <code>HMAC-SHA256</code> <code>Linux</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/MichaelGelaw/hplf-malloc">⚙️ hplf-malloc</a></h3>
      <p><b>High-Performance Concurrent Memory Allocator</b></p>
      <ul>
        <li>Linux C11 memory allocator with segregated slabs, thread-local caches, and lock-free batch transfers.</li>
        <li>Replaced quadratic reclamation with linear-time algorithm and atomics, reducing WSL2 trim latency from <b>546s to under 0.4s</b>.</li>
        <li>Evaluated across GCC, Clang, ASan, UBSan, TSan, and a <b>150M-operation stress suite</b>.</li>
      </ul>
      <p><b>Tech:</b> <code>C11</code> <code>Linux Kernel</code> <code>Atomics</code> <code>ASan/TSan</code> <code>Concurrency</code></p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/MichaelGelaw/VisionAID">👁️ VisionAID</a></h3>
      <p><b>Real-Time On-Device Assistive AI for Visually Impaired</b></p>
      <ul>
        <li>Edge computer vision assistant providing real-time spatial audio navigation prompts.</li>
        <li>Combines quantized scene recognition, hazard localization, OCR, and YOLOv11 object tracking into sub-50ms mobile inference.</li>
      </ul>
      <p><b>Tech:</b> <code>Flutter</code> <code>TFLite</code> <code>YOLOv11</code> <code>PyTorch</code> <code>Audio ML</code></p>
    </td>
  </tr>
</table>

---

## 💼 Experience & Research

- **Research Assistant** — *University of Dubai* `(Dec 2025 — Present)`
  - Edge occupancy tracking on **Jetson Orin Nano** with MQTT telemetry.
  - Smart space automation integrating **Matter-compatible sensors, ESP32 microcontrollers**, and Home Assistant.
  - Unified web UI combining **local LLMs (Ollama)** with real-time sensor streams and room digital twin.

- **Research Assistant** — *University of Dubai* `(Sep 2025 — Dec 2025)`
  - Engineered an audio respiratory disease detection system leveraging state-space **Mamba architecture**.
  - Processed and analyzed large-scale clinical audio datasets for enhanced model diagnostic robustness.

- **Back-End Intern** — *Kuraz Tech* `(Jul 2025 — Oct 2025)`
  - Architected backend for a gamified professional Q&A platform using **Laravel**.
  - Engineered secure authentication, relational database management, and high-throughput RESTful APIs.

---

## 🛠️ Technical Stack

```
Languages                 : Python, C, Java, JavaScript, TypeScript, SQL, PHP
Machine Learning & AI     : PyTorch, Transformers, CLIP, RAG, Ollama, Mamba, TFLite, Captum, Grad-CAM, Pytest
Systems & Infrastructure  : Linux, Docker, Kubernetes, Git, AWS, PostgreSQL, Redis, Supabase, SSE
Embedded & Edge IoT       : NVIDIA Jetson Orin Nano, ESP32, MQTT, Matter, Home Assistant
Frontend & Mobile         : React, Next.js, React Native, Flutter
```

---

## 🎓 Education & Coursework

**University of Dubai** — *B.S. in Computer Engineering* `(2023 — Present)`
- **GPA:** **3.97 / 4.0**
- **Relevant Coursework:**
  - Machine Learning & Deep Learning
  - Data Structures and Algorithms
  - Operating Systems & Concurrency
  - Computer Architecture
  - Embedded Systems
  - Signal Processing & Digital Signal Processing (DSP)

---

## 📬 Connect With Me

- 🌐 **Portfolio:** [michaelgelaw.github.io](https://michaelgelaw.github.io/)
- 📄 **Curriculum Vitae:** [Download PDF](https://michaelgelaw.github.io/Michael-Gelaw-CV.pdf)
- 💼 **LinkedIn:** [linkedin.com/in/MichaelGelaw](https://linkedin.com/in/MichaelGelaw)
- 🐙 **GitHub:** [github.com/MichaelGelaw](https://github.com/MichaelGelaw)
- ✉️ **Email:** [michaeldessie96@gmail.com](mailto:michaeldessie96@gmail.com)
- 📱 **Phone:** +971-568-517659
