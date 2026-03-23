# R Peak Detection using CNN

## Project Overview

This project implements **R-Peak Detection in ECG signals using Convolutional Neural Network (CNN)**.
The model is trained on the **MIT-BIH Arrhythmia Dataset** using the WFDB library.

The goal of this project is to detect R-peaks accurately for future use in
real-time ECG analysis and FPGA-based implementation.

---

##  Model Used

* Convolutional Neural Network (CNN)
* Framework: PyTorch
* Language: Python
* Notebook: Jupyter

---

##  Project Structure

CNN_R_PEAK_PROJECT/

* cnn_r_peak_new.ipynb
* CNN R peak.ipynb
* cnn_rpeak_model.pth
* requirements.txt
* README.md
* .gitignore

---

##  Dataset

Dataset used:

* MIT-BIH Arrhythmia Database
* Loaded using WFDB

Dataset is downloaded automatically using:

```python
wfdb.dl_database("mitdb", "data")
```

---

##  Steps in Project

1. Import libraries
2. Download MIT-BIH dataset
3. Load ECG signal
4. Create training windows
5. Build CNN model
6. Train model
7. Predict R-peaks
8. Plot results

---

##  Results

The CNN model successfully detects R-peaks in ECG signals.

Outputs:

* ECG signal plot
* R-peak prediction
* Training loss graph
* Saved model (.pth)

Example result:


<img width="980" height="374" alt="image" src="https://github.com/user-attachments/assets/61f41f80-e2f4-4f2d-90b9-8d0999a4bf3a" />


---

##  How to Run

Install libraries:

```
pip install numpy matplotlib torch wfdb scikit-learn
```

Run notebook:

```
cnn_r_peak_new.ipynb
```

---

##  Applications

* ECG analysis
* Heartbeat detection
* Biomedical signal processing
* Deep learning research
* FPGA implementation (future work)

---

##  Author

Shreya Sharma
Electronics and Communication Engineering
Deep Learning | FPGA | Biomedical Signal Processing

---
