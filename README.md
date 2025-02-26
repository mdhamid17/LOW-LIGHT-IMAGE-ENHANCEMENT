# Low-Light Image Enhancement using Deep Learning

## Overview
This project focuses on enhancing images captured in **low-light conditions** using **deep learning techniques**. The model is based on **R2RNet**, which integrates spatial and frequency domain information to improve contrast, reduce noise, and preserve details.

## Features
- **Low-Light Image Enhancement** using **R2RNet**
- **Contrast & Noise Reduction** with **Retinex-based decomposition**
- **Fourier Transform Integration** to retain high-frequency details
- **Trained on LOL dataset** (12,000 paired images)
- **Applications:** Surveillance, Medical Imaging, Autonomous Systems

## Technologies Used
- **Python**
- **TensorFlow / PyTorch**
- **OpenCV**
- **R2RNet (Deep Learning Model)**
- **Fourier Transform for Frequency Analysis**
- **LOL Dataset**

## Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/Low-Light-Enhancement.git
cd Low-Light-Enhancement

# Install dependencies
pip install -r requirements.txt
```

## Usage
```python
python enhance.py --input path_to_low_light_image --output enhanced_image.jpg
```

## Dataset
- This project utilizes the **LOL (Low-Light) Dataset**, which consists of **12,000 paired low-light and normal-light images**.
- You can download the dataset from: [LOL Dataset](https://www.kaggle.com/datasets/soumikrakshit/lol-dataset)

## Results (undergoing)
| Original Image | Enhanced Image |
|---------------|---------------|
| ![Original](images/original.jpg) | ![Enhanced](images/enhanced.jpg) |

## Future Work
- Improve **real-time processing speed**
- Enhance **generalization for different lighting conditions**
- Extend model for **video enhancement**

## Contributing
Feel free to contribute to this project by opening issues or submitting pull requests.


## Contact
For any queries, reach out to **Md Hamid** at mdhamid1752002@gmail.com
