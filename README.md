# Deep Image Prior
# PKU 2024 CV Final Project
# authors: 芮思铭，先鼎巍
Using DIP to solve image restoration tasks including Super Resolution, Denoising, Inpainting, and Neural Architecture Search.

## Features
- 🖼️ Multiple Image Restoration Tasks:
  - Super Resolution (SR)
  - Image Denoising
  - Image Inpainting
- 🧠 Neural Architecture Search (NAS)
- 📊 Multiple Evaluation Metrics
- 🔄 Skip Connection Optimization
- 📈 Real-time Training Visualization


## Installation

### Prerequisites
- Python 3.7+
- CUDA-capable GPU (recommended)
- 8GB+ RAM

### Dependencies
torch>=1.7.0
torchvision>=0.8.0
numpy>=1.19.0
matplotlib>=3.3.0
opencv-python>=4.5.0
tensorboard>=2.4.0
scikit-image>=0.18.0
lpips>=0.1.3

### Usage
- inpainting: run inpainting.ipynb
- denoising: run denoising.ipynb
- super resolution: run super_resolution.ipynb

### Setup Environment
```bash
# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

