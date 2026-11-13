## Hi, I'm Bo-Wei Lai (賴鉑崴) 👋

🌐 **Homepage:** [s9988766-creator.github.io](https://s9988766-creator.github.io)  ·  📄 [CV](https://s9988766-creator.github.io/cv/Bo-Wei_Lai_CV.pdf)  ·  🎓 [Google Scholar](https://scholar.google.com/citations?user=9zjp-a0AAAAJ)

Department of Biomedical Engineering, **National Yang Ming Chiao Tung University**, Taiwan.

I work on **deep learning for medical image analysis**, mainly **deformable brain MRI registration** and **auditing what medical CNNs actually learn**. I'm interested in what accuracy numbers hide (deformation folding, shortcut features, attention that misses the lesion), and I prefer controlled, reproducible comparisons over leaderboard comparisons.

### 📄 Publications & manuscripts

- **Do CNNs Learn Clinically Meaningful Imaging Representations? A Portable Multi-level Representation Audit for Brain Tumor MRI Classification**<br>
  **Bo-Wei Lai**, Li-Fen Chen<br>
  *MICCAI 2026 Workshop on Machine Learning in Clinical Neuroimaging (MLCN)*
  · [paper (open access)](https://papers.miccai.org/miccai-2026-sat/paper/MLCN_2026_035.pdf)
  · [project page](https://github.com/s9988766-creator/MLCN-MICCAI2026-brain-tumor-audit)<br>
  <sub>A retraining-free audit of a ResNet-50 (96.46% patient-level 5-fold accuracy) using out-of-fold embeddings: fine-tuning raises radiomic alignment about fourfold, and shifted-input controls show attention follows meningioma and pituitary tumors while glioma attention stays diffuse.</sub>

- **Where Should Iterative Registration Refine? A Controlled Analysis of the Accuracy–Topology Front**<br>
  **Bo-Wei Lai**, Ming-Chang Chiang, Po-Kai Yang<br>
  *Submitted to IEEE ISBI 2027 (under review)*
  · [code & per-subject results](https://github.com/s9988766-creator/IEEE-ISBI2027-iterative-registration)<br>
  <sub>Stationary-velocity refinement keeps +0.0758 Dice (95% CI [0.0720, 0.0799]) over displacement refinement at zero interior folding; 46 training runs with seed-and-subject bootstrap CIs.</sub>

- **A Matched-Protocol Ablation of Deep Brain MRI Registration: Supervision, Step Composition, and Deformation Regularity**<br>
  **Bo-Wei Lai**, Ming-Chang Chiang, Po-Kai Yang<br>
  *GCBME 2026, Annual Meeting of the Taiwanese Society of Biomedical Engineering*
  · [paper](https://github.com/s9988766-creator/GCBME2026-brain-registration/blob/main/docs/GCBME2026_Lai_Chiang_Yang.pdf)
  · [code & per-subject results](https://github.com/s9988766-creator/GCBME2026-brain-registration)<br>
  <sub>Reproduces all 11 published TransMorph-IXI benchmark numbers; composing rather than adding velocity steps reduces folding 48.8× at a matched backbone.</sub>

### 🔬 Other projects

- [Course project: Mammography mass classification on CBIS-DDSM](https://github.com/s9988766-creator/CourseProject-ml-mammography) (Machine Learning Algorithms and Applications, Prof. Shin-Jye Lee, Feb–Jun 2026): nine-person team project comparing hand-crafted features + KNN (malignant recall 59.5% → 83.8% after tuning) with transfer-learned CNNs (best test AUC 0.77)
- [Neuroimaging research notes](https://github.com/s9988766-creator/neuroimaging-research-notes): paper readings and notes on neuroimaging analysis and generative models

### 🛠️ Tools

Python · PyTorch · NumPy / SciPy · nibabel · VoxelMorph / TransMorph · FreeSurfer labels · statistical testing (paired tests, bootstrap)

---

This repository hosts the source of the homepage above (static HTML on GitHub Pages).
