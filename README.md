## Michele Maria De Giulio

PhD student at Università Cattolica del Sacro Cuore (Rome) · MSc in Biomedical Engineering

I build machine learning and physics-based models for medical imaging: physics-informed networks for quantitative MRI, Monte Carlo dosimetry, and clinical classifiers that report their uncertainty. Each project is evaluated against an explicit baseline, on data split so that no patient or subject appears in both training and test, with the limitations stated in the README.

### Research and physics

| Project | What it is | Key result |
|---|---|---|
| [pinn-qmri](https://github.com/mdegiulio97/pinn-qmri) | Unsupervised physics-informed network for T2/T2* relaxometry vs per-pixel least squares | Real multi-echo brain MRI (OpenNeuro ds007116): held-out-echo NRMSE 0.075 vs 0.100 |
| [g4-brain-dosimetry](https://github.com/mdegiulio97/g4-brain-dosimetry) | Geant4 Monte Carlo photon dosimetry on MRI-derived brain phantoms, atlas-based regional dose (C++ / Python) | 6 MV water depth dose vs BJR-25: gamma (2%/2 mm) pass rate 100% |

### Applied ML for medical imaging

| Project | What it is | Key result |
|---|---|---|
| [medical-xai-uncertainty](https://github.com/mdegiulio97/medical-xai-uncertainty) | ResNet18 with MC-Dropout uncertainty, temperature scaling and Grad-CAM | Brain MRI glioma vs non-glioma, split by patient (209 patients): AUROC 0.942 vs 0.846 baseline |
| [genai-mri-superres](https://github.com/mdegiulio97/genai-mri-superres) | ESPCN/SRCNN image super-resolution vs bicubic | Real T1w brain MRI, held-out subject: +0.52 dB PSNR |
| [phasor-flim-explorer](https://github.com/mdegiulio97/phasor-flim-explorer) | Fit-free phasor analysis and unmixing of FLIM data vs NNLS fitting | Lower unmixing error than NNLS at every photon count, ~23× faster (synthetic ground truth) |
| [rag-radiology-reports](https://github.com/mdegiulio97/rag-radiology-reports) | Local, offline retrieval-augmented generation over radiology reports with source citations | Functional check on a synthetic corpus |

Shared base: [ml-clinical-template](https://github.com/mdegiulio97/ml-clinical-template) (uv + locked dependencies + ruff/pytest CI). Overview: [clinical-ml-portfolio](https://github.com/mdegiulio97/clinical-ml-portfolio).

University coursework (archived): [parkinson-voice-classifier](https://github.com/mdegiulio97/parkinson-voice-classifier) (subject-level evaluation and why record-level splits leak) · [Health-Insurance](https://github.com/mdegiulio97/Health-Insurance) (regression with a baseline).

### Tools

Python · PyTorch · scikit-learn · NumPy / SciPy · Geant4 (C++) · Streamlit · uv · Git / GitHub Actions

### Contact

mdegiulio97@gmail.com · [LinkedIn](https://www.linkedin.com/in/michele-maria-de-giulio-528881208)
