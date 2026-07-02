## Hi, I'm Michele De Giulio 👋

**PhD student @ Università Cattolica del Sacro Cuore (UNICATT) · MSc in Biomedical Engineering**

I build **methodologically rigorous machine learning for biomedical and clinical imaging** — from physics-informed models and phasor signal analysis to explainable, uncertainty-aware clinical classifiers.

My through-line is *breadth as depth*: **one technique, one clean and reproducible project, always compared against an honest baseline** — with the limitations stated up front.

---

### 🔬 Research interests

- **Physics-informed & Scientific ML (SciML)** — embedding forward physical models into learning (qMRI relaxometry, Bloch dynamics)
- **Phasor analysis** — fit-free signal decomposition for MRI and FLIM microscopy
- **Digital twins** of metabolism and disease progression — cross-scale, physics-grounded modelling
- **Trustworthy clinical ML** — calibration, uncertainty quantification, explainability
- **GenAI & RAG** for clinical / radiology text

---

### 🧪 Clinical ML Portfolio

One technique per repository — reproducible (`uv` + locked dependencies + fixed seeds), tested (CI: `ruff` + `pytest`), and evaluated against a baseline.

| Project | Technique | In short |
|---|---|---|
| [genai-mri-superres](https://github.com/mdegiulio97/genai-mri-superres) | GenAI / image-to-image | MRI super-resolution (ESPCN/SRCNN) vs bicubic — PSNR/SSIM |
| [pinn-qmri](https://github.com/mdegiulio97/pinn-qmri) | Physics-Informed NN | Unsupervised T2 relaxometry vs per-pixel least-squares |
| [cxr-xai-uncertainty](https://github.com/mdegiulio97/cxr-xai-uncertainty) | XAI + uncertainty | Explainable chest-X-ray classifier: MC-Dropout, calibration, Grad-CAM |
| [rag-radiology-reports](https://github.com/mdegiulio97/rag-radiology-reports) | RAG / NLP | Local, offline RAG over radiology reports with source citations |
| [phasor-flim-explorer](https://github.com/mdegiulio97/phasor-flim-explorer) | Signal processing | Fit-free phasor analysis and unmixing of FLIM data |
| [Parkinson-Classificator](https://github.com/mdegiulio97/Parkinson-Classificator) | Classification | Parkinson's detection from voice measures — 3 models vs baseline |
| [Health-Insurance](https://github.com/mdegiulio97/Health-Insurance) | Regression | Medical-cost prediction — linear + ensemble vs baseline |

▶ Start here: **[clinical-ml-portfolio](https://github.com/mdegiulio97/clinical-ml-portfolio)** (portfolio overview) · reusable base: [ml-clinical-template](https://github.com/mdegiulio97/ml-clinical-template)

---

### 🛠️ Tools

`Python` · `PyTorch` · `scikit-learn` · `NumPy` / `SciPy` · `JAX` · `Streamlit` · `uv` · `Geant4` · `Git` / GitHub Actions

---

### 📫 Contact

- 📧 byome@chirale.it

> *A principle I hold across everything I ship: reproducible pipelines, honest baselines, and limitations stated up front.*
