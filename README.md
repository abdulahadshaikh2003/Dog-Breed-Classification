# 🐶 Dog Breed Classifier

A deep learning model that classifies dog breeds from images using PyTorch and transfer learning.

# Features
- Classifies 120+ dog breeds
- Uses EfficientNet-B0 with transfer learning
- Handles corrupted/inaccessible images gracefully
- Achieves ~80% validation accuracy with minimal training

# Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/abdulahadshaikh2003/Dog-Breed-Classification.git
   cd dog-breed-classifier


   🏗️ Project Structure
dog-breed-classifier/
├── dog_images/            # Dataset (not included in repo)
│   └── Images/            # Extracted dataset
├── models/                # Saved models
│   └── best_model.pth
├── utils/                 # Utility scripts
│   ├── dataset_cleaner.py
│   └── visualization.py
├── dog_breed_classifier.py # Main training script
├── predict.py             # Inference script
└── README.md

✉️ Contact
abdulahadshaikh2003@gmail.com
