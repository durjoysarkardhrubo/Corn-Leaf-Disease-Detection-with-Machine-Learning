# Corn Leaf Disease Detection with Machine Learning

Detects and classifies corn leaf diseases using machine learning to help farmers identify and manage plant health effectively.

## Features

- **Image Classification:** Identifies healthy and diseased corn leaves.
- **Easy Deployment:** Simple setup and usage.
- **Custom Training:** Train with your own dataset.

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/corn-leaf-disease-detection.git
    cd corn-leaf-disease-detection
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Download Dataset:**
    - [Download Here](https://link_to_dataset.com)
    - Organize as:
      ```
      /dataset
        /healthy
        /blight
        /rust
        ...
      ```

## Usage

### Train the Model
```bash
python train.py --dataset_path path_to_dataset
