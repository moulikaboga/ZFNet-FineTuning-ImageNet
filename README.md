# ZFNet-FineTuning-ImageNet
This repository showcases fine-tuning the ZFNet convolutional neural network on a subset of the ImageNet dataset. It includes training, evaluation, and visualization of intermediate feature maps to understand feature extraction at different layers


---

## Key Features
- Implementation of the ZFNet architecture.
- Fine-tuning on a small ImageNet subset for efficient experimentation.
- Visualization of feature maps to analyze layer outputs and understand feature extraction.

## Project Structure
```
ZFNet-ImageNet-FineTuning/
│
├── DL_Assignment(Final).pdf     # Project detailed documentation
│
├── DeepLearning.ipynb           # Notebook for intermediate layer visualization and Main script for training and evaluation
│
├── requirements.txt             # List of required libraries
│
├── README.md                    # Project documentation
│
└── LICENSE                      # License for the repository
```

## Link to download the dataset
[Mini Imagenet Dataset](https://s3.amazonaws.com/fast-ai-imageclas/imagenette2.tgz)

## Prerequisites
- Python 3.8 or higher
- PyTorch
- Torchvision
- NumPy
- Matplotlib

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/moulikaboga/ZFNet-FineTuning-ImageNet.git
   cd ZFNet-FineTuning-ImageNet
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
### Training
Run the training script:
```bash
python main.py
```

### Visualizing Feature Maps
Use the `visualization.ipynb` notebook to explore intermediate layer outputs. You can analyze how the network processes and extracts features from the input images.
 

Example visualization from Conv1 layer:  
[Detailes Full Document in DL_Assignment(Final) Document](https://github.com/moulikaboga/ZFNet-FineTuning-ImageNet/blob/main/DL_Assignment(Final).pdf)

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgements
- The PyTorch library
- ImageNet dataset

---
