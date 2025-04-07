# 🎨 Painting in a Painting: Hidden Art Detection using AI

Welcome to the official repository for my **Google Summer of Code 2025** proposal under the organization **Humunai**. This project is focused on the intersection of art conservation and artificial intelligence — using modern AI techniques to detect and reconstruct hidden paintings buried beneath visible layers in classical artworks.

Self Link: [View GSoC Proposal Draft](https://docs.google.com/document/d/1vAAgtQcbNdg5CTDqjHOrLTU7Gv3si86fZiniWb0VFKk/edit?usp=sharing)
---

## 🧠 Project Abstract

In the realm of cultural heritage, many historical artworks conceal earlier paintings or sketches beneath their visible layers. These hidden stories, obscured by time and brushstrokes, can be revealed through multispectral and X-ray imaging. However, manually analyzing such complex image data is slow, requires significant expertise, and is prone to human error.

This project proposes an AI-powered, modular pipeline that automates the detection — and optionally, the reconstruction — of hidden imagery within paintings. Using **PCA** for feature extraction, **CNNs** for classification, and (optionally) **GANs** for reconstruction, the tool aims to assist researchers and conservationists with an open-source solution that makes spectral data analysis accessible, efficient, and insightful.

---

## 🎯 Goals

- Develop a robust, modular pipeline for hidden image detection.
- Automate feature extraction and classification from spectral image data.
- Enable (optional) reconstruction of obscured layers using generative models.
- Deliver a well-documented, open-source toolkit for researchers in the heritage and art community.

**Non-Goals**:  
- Real-time inference  
- Commercial deployment  
- Mobile/embedded device optimization

---


## 📅 Project Timeline

- **Community Bonding (May 20 – June 16)**  
  Finalize dataset, refine architecture, and sync with mentors.

- **Phase 1 (June 17 – July 15)**  
  ✅ Data preprocessing pipeline  
  ✅ Implement PCA-based feature extraction  
  ✅ Initial CNN model training

- **Mid-Term Evaluation (July 15 – July 22)**  
  📊 Documentation, testing, and review

- **Phase 2 (July 23 – August 18)**  
  ✅ Advanced classification tuning  
  ✅ Integrate optional GAN reconstruction  
  ✅ Visualization tools

- **Final Submission (August 19 – August 26)**  
  🗂️ Final codebase, evaluations, and demo notebook

---

## 📊 Evaluation Metrics

- Classification Accuracy (CNN)
- Peak Signal-to-Noise Ratio (PSNR)
- Structural Similarity Index (SSIM)
- Visual inspection & validation by sample reconstructions
- Robustness across diverse spectral inputs

---

## 🗂 Repository Structure

```
📦 hidden-art-ai/
 ┣ 📁 data/              → Sample image datasets
 ┣ 📁 src/               → Main pipeline code (PCA, CNN, GAN)
 ┣ 📁 notebooks/         → EDA, experiments, and demos
 ┣ 📁 models/            → Trained model checkpoints
 ┣ 📁 docs/              → Proposal, Gantt chart, architecture
 ┣ 📄 requirements.txt   → Python dependencies
 ┣ 📄 README.md          → Project documentation
```

---

## 🤝 Why Humunai?

Humunai’s dedication to merging humanities with AI resonates deeply with the mission of this project. Their focus on digital heritage makes them an ideal ecosystem to develop tools that empower art conservationists, archivists, and historians with AI-driven insights.

---

## 📨 Communication Plan

- **Timezone**: IST (UTC+5:30)  
- **Working Hours**: 10 AM – 6 PM (flexible on mentor availability)  
- **Email**: krisha22102005@gmail.com    
- **Progress Updates**: GitHub issues, weekly commits, regular syncs

---

## 📚 References

- Wikipedia – [Multispectral Imaging](https://en.wikipedia.org/wiki/Multispectral_imaging)  
- Stanford CS231n – [CNNs](https://cs231n.github.io/convolutional-networks/)  
- MIT License – [Open Source Licensing](https://opensource.org/license/mit/)

---

## 📝 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---
