# Archery Motion Analysis Dataset

This repository contains `.npy` data files used in the research titled:

**"Development and Application of a Deep Learning Sequence Network Model for Enhancing Archery Performance"**  
by Jihoon Park (Yongin University) and Hyongjun Choi (Dankook University)

## 📘 Description

The dataset includes joint coordinate data extracted from video recordings of four national-level Korean archers. The data was collected using real-time pose estimation techniques and preprocessed for deep learning sequence model training.

Key features:
- 17 joint coordinates per frame, normalized and filtered.
- Sequence data from the "ready" position to "release."
- Used for training RNN, LSTM, GRU, Bi-LSTM, and Bi-GRU models.
- Data sampling at 60 FPS for precision motion analysis.

## 📂 Files

- `x_train.npy` — Training input sequences  
- `x_test.npy` — Testing input sequences  
- `y_train.npy` — Training labels  
- `t_test.npy` — Testing labels

## 🔗 Download

Due to file size limitations on GitHub, the full `.npy` dataset is hosted on Google Drive:  
- [Download](https://drive.google.com/drive/folders/1Rt0ASiSedD3RojwNbAEalCEy1VBrK6Eu?usp=drive_link)  


## 📧 Contact

📨 Jihoon Park,   Ph.D. — [analysispark@gmail.com](mailto:analysispark@gmail.com)
📨 Hyongjun Choi, Ph.D. — [chj2812@dankook.ac.kr](mailto:chj2812@dankook.ac.kr)
