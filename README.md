# Hi there, I'm Carlos Moreno García 👋

[![Scholar](https://img.shields.io/badge/Google_Scholar-Carlos_Moreno_Garc%C3%ADa-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=9LATVmYAAAAJ&hl=es)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-carlosmorenodti-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carlosmorenodti/)
[![Email](https://img.shields.io/badge/Email-carlos.moreno%40dti.uhu.es-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:carlos.moreno@dti.uhu.es)

**AI Researcher | Medical Computer Vision & Clinical NLP**  
📍 *I2C Research Group, University of Huelva, Spain*

I design robust, uncertainty-aware Deep Learning systems for healthcare. My core research tackles **diagnostic ambiguity in medical imaging** through **hierarchical multimodal fusion**, aligning high-resolution radiological findings (CXR) with clinical reports to build trustworthy, interpretable Computer-Aided Diagnosis (CAD) models.

---

## 🔬 Research Interests & Core Expertise

- **Multimodal Medical Alignment:** Dual-Transformer pipelines (ViT + BioBERT), Vision-Language Pre-training (VLP), and Cross-Modal Attention.
- **Uncertainty-Gated Inference:** Dynamic decision arbitration using visual entropy/confidence thresholds ($\tau$) to rescue ambiguous visual predictions via clinical context.
- **Robust Medical NLP:** Concept Blinding (regularized label masking) to mitigate shortcut learning and lexical leakage in radiological report comprehension.
- **Clinically-Grounded XAI:** Semantic-visual coherence, alignment between token-level report findings and localized image pathology.

---

## 📚 Highlighted Research & Open Source

### 🫁 [Reducing Diagnostic Ambiguity via Multimodal Fusion](https://github.com/CarlosmDTI/Adaptive_Multimodal_Fusion_in_Radiology)
*A Framework for Alignment and Coherence between Radiological Findings and Clinical Reports*

- **Focus:** Resolving visual modality bias and opacity overlap in Chest X-Rays using selective textual arbitration.
- **Architecture:** Vision Transformer (ViT-Base) + BioBERT v1.1 + Uncertainty-Gated Ensemble.
- **Key Results on PadChest (Expert-Validated Cohort):**
  - **F1-Score: 0.97** overall weighted average, outperforming unimodal vision baselines.
  - **87% Sensitivity on Pneumonia**, effectively recovering false negatives where image alone was inconclusive.
  - Zero performance trade-off on high-confidence structural pathologies (Fibrosis F1: 0.99).
- **Artifacts:** Code, pipeline configs, and reproduction scripts available in the repository.

---

## 🛠️ Stack & Research Toolkit

| Category | Tools & Frameworks |
|---|---|
| **Core & Deep Learning** | Python, PyTorch, Hugging Face Transformers, Torchvision, Scikit-learn |
| **Vision & Language Encoders** | Vision Transformers (ViT), BioBERT, ClinicalBERT, CNN Backbones (DenseNet, ResNet) |
| **Medical Imaging & Data** | PadChest, MIMIC-CXR, CheXpert, DICOM processing, TorchIO, Albumentations |
| **Scientific Tooling** | Git, Weights & Biases (W&B), JupyterLab, LaTeX, TikZ, Overleaf |

---

## 🤝 Let's Collaborate

I am always open to discussing multimodal representation learning, foundation models in healthcare, and scientific collaborations.

- 💬 Inquiries: **carlos.moreno@dti.uhu.es**
- 🌐 University Profile: [I2C Research Group — Universidad de Huelva](http://www.uhu.es)
