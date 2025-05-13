# fPCG-ML (fetal PhonoCardioGraph analysis with ML techniques)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://example.com)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

This repository contains the implementation code and experimental results for the paper:
**"Fetal Heart Rate Estimation in Phonocardiograms Using Deep Learning and Digital Signal Processing"** by _authors names_. The paper can also be found in the repository as **Paper.pdf** when it's published.

<!-- (Published in [Journal/Conference Name], [Year]). -->

## 📄 Abstract

Fetal heart rate monitoring through phonocardiograms enables a non-invasive assessment of fetal health, aiding in the early detection of potential complications during pregnancy. However, the extraction of fetal heart signals is hindered by various noise sources, such as maternal heart sounds and ambient noise, making accurate frequency estimation difficult. This study proposes a regression model based on Convolutional Neural Networks, leveraging MFCC and Delta-MFCC coefficients extracted from prefiltered audio segments (band pass and wavelet filtering). In addition, a data augmentation technique was applied to address the scarcity of labeled instances. Experiments were conducted using the SUFHSDB dataset, achieving a mean absolute error of $4.02 \pm 0.24$ bpm. The results suggest that deep learning-based approaches, combined with data augmentation, are promising for the estimation of fetal heart rate.

## 📂 Repository Structure

```
.
├── data/
│   ├── raw_database/   # Insert original database (Physionet)
│   ├── denoized_database/
│   ├── denoized_augmented_database/
│   └── README.md
│     
├── notebooks/
│   ├── dataset_cleaning.ipynb
│   ├── dataset_separation.ipynb
│   ├── dataset_separation_augmented.ipynb
│   ├── model_training.ipynb
│   └── README.md
│
├── Paper.pdf
└── README.md
```

## 📊 Reproducing Results

1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository-name.git
   ```
2. Follow the data preparation instructions in `data/README.md`
3. Follow the variables and parameters intructions in `notebooks/README.md`
4. Execute notebook cells in order
5. Results of experiment will be shown at the end of `notebook/model_training.ipynb`

## 📝 Citation (June 06, 2025)

1. Paper being written ✏️
2. Paper submission (May 12, 2025) 📅
3. Paper accepted (June 06, 2025) 📅
<!--
If you use this work in your research, please cite:

```bibtex
@article{citationkey,
  title   = "{Paper Title}",
  author  = "{Author Names}",
  journal = "{Journal Name}",
  volume  = "{Volume}",
  number  = "{Number}",
  pages   = "{Pages}",
  year    = "{Year}"
}
```
-->
## 🤝 Contributing

Contributions are welcome! Please open an issue first to discuss proposed changes.

## 📜 License

This project is licensed under the MIT License.

## 📧 Contact

<!-- FullName • Email • Instituition -->

---
