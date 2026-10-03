# Tumor Detection and Progression Prediction

A Hybrid Quantum-Classical Convolutional Neural Network (QCNN) for brain tumor detection, combining classical deep learning feature extraction with quantum variational circuits.

## Architecture

- **Classical Feature Extractor**: Conv2D → MaxPooling → Flatten → Dense
- **Quantum Layer**: 4-qubit variational quantum circuit (PennyLane KerasLayer)
- **Classifier**: Dense softmax output for binary classification

## Requirements

- Python 3.10
- TensorFlow 2.13.1
- PennyLane 0.34.0
- scikit-learn 1.3.0

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook main_hybrid_qcnn.ipynb
```

## License

MIT
