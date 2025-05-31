# G11_ASL_GSGD_CNN

Group 11 - American Sign Language (ASL) Detection using CNN with GSGD Optimizer

Group Members:
Tapnaanshu Lal S11209475
Divyesh Kumar Mistry  S11209141 
Shiva Narayan  S11208843
Jashwin Singh  S11209297

This project presents the implementation of a deep learning model for recognizing **American Sign Language (ASL)** hand signs using a **Convolutional Neural Network (CNN)** trained with a custom **Guided Stochastic Gradient Descent (GSGD)** optimizer.

The original concept of GSGD was inspired by the [GSGD-CNN MATLAB repository](https://github.com/anuraganands/GSGD-CNN). This implementation is an independent re-creation using Python and TensorFlow, designed to run entirely on **Google Colab**.

---

## Objective

To build an efficient and accessible system for ASL hand sign recognition using deep learning, and explore the application of the GSGD optimizer in Python-based neural networks.

---

## How to Run This Notebook

### Step 1: Open in Google Colab

1. Visit [Google Colab](https://colab.research.google.com/)
2. login with your Colab Account.
3. Click on **“File” → “Upload notebook”**
4. Upload the file named: `G11_ASL_GSGD_CNN.ipynb`

### Execute the Code

- Once uploaded, click **“Runtime” → “Run all”** to execute all the cells sequentially.
- Follow any prompts or notes in the notebook (e.g., dataset setup).

---

## Notebook Contents

The notebook includes the following sections:

1. **Project Overview**
2. **ASL Dataset Preparation**  
   - Dataset used: [Kaggle ASL Alphabet Dataset](https://www.kaggle.com/datasets/grassknoted/asl-alphabet)
3. **Model Architecture**
   - CNN layers for feature extraction
   - GSGD Optimizer integration
4. **Training & Evaluation**
   - Visualization of training accuracy and loss
5. **Conclusion & References**

> The notebook is self-contained and does not require any external Python scripts.

---

## Requirements

- Runs entirely on Google Colab (no local installation required)
- Internet connection for dataset download
- Libraries used: `TensorFlow`, `NumPy`, `Matplotlib`, `Keras`, `Pandas`

---

## References

- Original Optimizer: [GSGD-CNN (MATLAB)](https://github.com/anuraganands/GSGD-CNN)
- Dataset Source: [ASL Alphabet – Kaggle](https://www.kaggle.com/datasets/grassknoted/asl-alphabet)

---

