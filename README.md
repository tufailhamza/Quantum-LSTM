# Quantum Long Short-Term Memory (QLSTM)

This project implements the Quantum Long Short-Term Memory (QLSTM) model, a quantum-inspired deep learning architecture designed to enhance the performance of classical LSTM models using quantum computing principles. The QLSTM is inspired by the classical Long Short-Term Memory (LSTM) networks commonly used in tasks like natural language processing and speech recognition.

## **Project Overview**

Quantum computing has the potential to revolutionize the field of deep learning by offering faster and more efficient models. One promising application of quantum computing in machine learning is the development of **quantum neural networks**, which use quantum mechanics principles such as superposition and entanglement to process and learn from data. The **QLSTM** is one such quantum neural network designed to address the limitations of classical LSTMs and enable more efficient training and inference on quantum computing platforms.

The main objective of this project is to implement and evaluate the QLSTM model, as proposed in the paper *"Quantum Long Short-Term Memory"* by S. Chen, and explore its potential in deep learning tasks such as sequence classification and language modeling. The evaluation is conducted on well-known datasets like **IMDB Movie Review** (for sentiment analysis) and **WikiText** (for language modeling).

---

## **Group Members**

- Muhmmad Hamza k213293
- Muhammad Talha Shaikh k214564
- syed Bilal Ali k213153



---

## **Features**

- **Quantum LSTM Architecture**: A novel quantum-inspired version of the classical LSTM network.
- **Integration with Quantum Computing Platforms**: The model is designed to run on quantum computing platforms.
- **Evaluation on Benchmark Datasets**: Implementation and testing on datasets such as IMDB and WikiText.
- **Comparison with Classical LSTM**: A comparison of the QLSTM’s performance against traditional LSTM models.

---
![image](https://github.com/shivalee12/Quantum-LSTM/assets/77015285/408346e0-2cb9-4375-93c0-fd210ddc6f41)


## **Installation**

### Prerequisites
Ensure that you have the following installed before running the code:
- Python 3.x
- Quantum computing library (e.g., `Qiskit`, `PennyLane`, or other suitable libraries)
- TensorFlow or PyTorch (for training neural networks)
- NumPy, Matplotlib, and other required Python packages

### Steps to Install
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Quantum-LSTM.git
    cd Quantum-LSTM
    ```
2. Create a virtual environment (optional but recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use venv\Scripts\activate
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

---

## **Usage**

### Running the QLSTM Model

To run the QLSTM model on the IMDB movie review dataset or WikiText dataset, use the following commands:

#### For Sentiment Analysis (IMDB Dataset):
```bash
python qlstm_imdb.py



