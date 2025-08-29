# Sign-Language-Detection
Masters Project: Secure and Adaptive Deep Learning Framework for Real-Time Continuous Sign Language Detection using IoT and Blockchain

#  Secure and Adaptive Deep Learning Framework for Real-Time Continuous Sign Language Detection using IoT and Blockchain

This repository contains a **Google Colab–ready** notebook for building a **real-time, secure, and adaptive sign language recognition system** using Deep Learning, IoT-based input, and Blockchain-based gesture logging.

 Developed as part of a **Master's-level research project** at Dublin City University.

---

##  Features

-  **Hybrid Deep Learning** architecture:
  - CNN for spatial features
  - BiLSTM for temporal sequence modeling
  - Transformer for attention-based context understanding
-  **Real-time input simulation** via webcam/sensor
-  **Adaptive Learning** with DAML-inspired dynamic feedback loop
-  **Blockchain Integration** for tamper-proof gesture logs
-  **Performance Evaluation** with:
  - Accuracy, F1-score, Inference Time, Blockchain Logging Time

---

##  Project Overview

The project addresses challenges in sign language recognition including:
- Lack of adaptability to new users
- Privacy and tamper-proofing of gesture logs
- Real-time performance on edge devices (e.g. Raspberry Pi)

Trained on datasets: **RWTH-PHOENIX**, **WLASL**, and **ASLLVD**.

---

##  How to Run in Google Colab

You can run the notebook without any local setup. Just follow these steps:

1. Visit: [https://colab.research.google.com](https://colab.research.google.com)
2. Click on the **GitHub** tab.
3. Paste this repo URL in the search box:

https://github.com/whatayoushrek/Sign-Language-Detection

yaml
Copy code

4. Open `SignDetection Code.ipynb`
5. (Optional) Enable GPU: `Runtime → Change runtime type → GPU`
6. Click `Runtime → Run all` to execute the full pipeline.

---

##  Output Files

After successful execution, the following output files will be available in the Colab Files panel:

- `gesture_classification_report.csv`
- `gesture_log_blockchain.json`
- Real-time prediction logs and charts

Download these manually from the left Files panel in Colab.

---

##  Requirements

**Google Colab:** No setup needed.

**To run locally:**

```bash
pip install -r requirements.txt
