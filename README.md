
# Fashion MNIST CNN with PyTorch

A Convolutional Neural Network (CNN) for classifying Fashion MNIST clothing images, built with PyTorch.

![Fashion MNIST Samples](results/samples.png)

## ✨ Features
- Custom CNN architecture with two convolutional blocks and MaxPooling
- Modular and clean code structure
- Training and evaluation pipeline
- Random sample predictions
- Model saving and loading
- Helper functions for accuracy calculation

## 🛠️ Technologies
- Python
- PyTorch
- torchvision
- Matplotlib
- tqdm
- NumPy

## 📊 Results
- **Test Accuracy**: ~88-90% (after 3 epochs)
- **Test Loss**: ~0.30-0.35
- **Epochs**: 3
- **Optimizer**: SGD (lr=0.1)

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/AIilK/fashion-mnist-cnn-pytorch.git
cd fashion-mnist-cnn-pytorch

# 2. Install dependencies
pip install torch torchvision torchaudio matplotlib tqdm numpy

# 3. Train the model
python train.py
```

## 📁 Project Structure
```
├── .gitignore
├── README.md
├── helper_functions.py
├── model.py
├── train.py
├── requirements.txt
├── data/                  # Automatically downloaded
├── models/                # Saved model (.pth)
└── results/               # Sample images & predictions
```

## 🔧 Future Improvements
- Add Data Augmentation
- GPU support (`torch.cuda`)
- Transfer Learning (ResNet, VGG, etc.)
- Experiment tracking with TensorBoard or Weights & Biases
- Web deployment with Streamlit or Gradio
- Confusion Matrix visualization

## 📚 References
Inspired by the official [PyTorch Deep Learning](https://github.com/mrdbourke/pytorch-deep-learning) course by Daniel Bourke.

## 👤 Author
**Alireza**  
[GitHub](https://github.com/AIilK)

---

⭐ If you found this project helpful, please give it a star!

---


اگر خواستی بخشی از README تغییر کنه (مثلاً accuracy دقیق مدلت، اسم کامل، یا لینک لینکدین) بگو تا سریع ویرایش کنم. 

حالا آماده‌ست؟ بریم سراغ `requirements.txt` یا چیز دیگه؟
