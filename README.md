# MNIST-CNN-CUDA
This project implements a **Convolutional Neural Network (CNN)** on the **MNIST handwritten digits dataset** using **PyTorch with CUDA acceleration**.  
It also includes **Grad-CAM visualization** to highlight which parts of the image the model focuses on when making predictions.  
The project was developed as part of my preparation for a **Master’s in Digital Healthcare**, to build experience with **AI for medical imaging**. 
   Features
- CNN model for MNIST digit classification
- GPU acceleration with CUDA
- Mixed precision training (PyTorch AMP)
- Evaluation with accuracy and confusion matrix
- Grad-CAM visualization for explainability

   Installation
Clone the repo and install the required dependencies:

```bash
git clone https://github.com/Kenkai993/MNIST-CUDA-CNN.git
cd MNIST-CUDA-CNN
pip install -r requirements.txt
