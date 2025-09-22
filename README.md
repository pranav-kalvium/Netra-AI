# Netra-AI 👁️‍🗨️

**Netra-AI** is an AI-powered solution designed for the early detection and staging of Diabetic Retinopathy (DR) from retinal images. Leveraging advanced machine learning, Netra-AI instantly classifies DR into clinically relevant categories—**No DR, Mild DR, Moderate DR, or Severe DR**—enabling accessible and rapid screening for all.

---

## 🩺 Project Purpose

Diabetic Retinopathy is a leading cause of preventable blindness, and early detection is critical. Netra-AI empowers clinicians and communities with:

- **Instant DR detection:** Get results within seconds.
- **Staging clarity:** Distinguishes between No DR, Mild DR, Moderate DR, and Severe DR.
- **Accessible Anywhere:** Designed for use in clinics, remote settings, and on standard computing devices.
- **Automated Reporting:** (Coming soon) Generates comprehensive, standardized reports with findings and recommendations.

Currently, this repository focuses on the core ML model for DR detection and staging.

---

## 🚀 Features

- **State-of-the-art ML Model:** Trained on diverse retinal datasets for robust DR classification.
- **Easy-to-Use Interface:** (CLI/Notebook) for image input and prediction.
- **Clear Predictions:** Outputs the specific DR stage for each image.
- **Extensible Pipeline:** Easily integrate with future reporting or deployment modules.
- **Fast & Lightweight:** Suitable for real-time, on-device inference.

---

## 🏗️ Directory Structure

```
Netra-AI/
├── data/                 # (Sample) Retinal images and data loaders
├── models/               # ML model architectures & weights
├── utils/                # Helper scripts and preprocessing
├── notebooks/            # Jupyter/Colab experiments and demos
├── main.py               # Entry point for inference/training
├── requirements.txt      # Python dependencies
├── tests/                # Unit and integration tests
└── README.md             # Project info
```

---

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/pranav-kalvium/Netra-AI.git
   cd Netra-AI
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## 🧑‍💻 Quick Start

**Run inference on a retinal image:**
```bash
python main.py --image path/to/retina.jpg
```
- The output will be one of: `No DR`, `Mild DR`, `Moderate DR`, or `Severe DR`.

**Try Jupyter notebook:**
- Explore `notebooks/` for interactive demos and experiments.

---

## 🏥 DR Stages Explained

| Stage      | Description                          |
|------------|--------------------------------------|
| No DR      | No signs of diabetic retinopathy     |
| Mild DR    | Microaneurysms only                  |
| Moderate DR| More than just microaneurysms, but less than severe |
| Severe DR  | Extensive retinal damage, urgent care advised |

---

## 🤖 Model Details

- **Input:** Retinal fundus images (JPEG/PNG)
- **Output:** DR stage (from 4 categories)
- **Model:** Deep neural network (see `models/`)
- **Training Data:** Public and/or custom annotated datasets

---

## 🌍 Roadmap

- [x] ML model for DR stage classification
- [ ] Automated PDF/HTML report generation
- [ ] Web/mobile interface
- [ ] Integration with medical databases

---

## 🤝 Contributing

- Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) (if available) or open an issue to discuss ideas.

---

## 🛡️ License

MIT License (see [LICENSE](LICENSE))

---

## 📫 Contact

- GitHub Issues: [Report bugs or request features](https://github.com/pranav-kalvium/Netra-AI/issues)
- Maintainer: [@pranav-kalvium](https://github.com/pranav-kalvium)

---

> **Netra-AI** – Making sight-saving technology accessible, instant, and accurate.
