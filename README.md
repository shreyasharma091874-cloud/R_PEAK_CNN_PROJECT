# R Peak Detection using CNN

##  Project Overview

This project implements **R-Peak Detection in ECG signals using Convolutional Neural Network (CNN)**.
The model is trained on the **MIT-BIH Arrhythmia Dataset** and predicts the location of R-peaks in ECG signals.

This project is part of my work in ** Deep Learning / FPGA-based ECG analysis**.

---

##  Model Used

* Convolutional Neural Network (CNN)
* Framework: PyTorch
* Language: Python
* Notebook: Jupyter

---

##  Project Structure

```
CNN_R_PEAK_PROJECT/
│
├── cnn_r_peak_new.ipynb
├── CNN R peak.ipynb
├── cnn_rpeak_model.pth
├── download_mitbih.py
├── data/
├── model/
├── code/
```

---

##  Dataset

Dataset used:

* MIT-BIH Arrhythmia Database
* Source: PhysioNet

ECG signals are loaded using `wfdb` library.

---

##  Steps in Project

1. Import libraries
2. Load MIT-BIH ECG data
3. Preprocess signal
4. Generate training windows
5. Build CNN model
6. Train model
7. Predict R-peaks
8. Plot results

---

##  How to Run

Install dependencies:

```
pip install numpy matplotlib torch wfdb
```

Run notebook:

```
cnn_r_peak_new.ipynb
```

---

##  Output

* Predicted R-peaks
* ECG signal plot
* Training loss graph
* Model saved as `.pth`

---

##  Applications

* ECG analysis
* Heartbeat detection
* FPGA implementation
* Biomedical AI
* Real-time monitoring

---

##  Author

Shreya Sharma
Electronics & Communication Engineering
Deep Learning | FPGA 

---
