# Image Tampering Recognition using YOLOv5

This repository contains an implementation of image tampering recognition using YOLOv5, based on the paper ["Image Tampering Recognition Algorithm using Improved YOLOv5"](https://ieeexplore.ieee.org/document/10238704) by Z. Liu.

## Paper Information

- **Title**: Image Tampering Recognition Algorithm using Improved YOLOv5
- **Paper Link**: [IEEE Xplore](https://ieeexplore.ieee.org/document/10238704)
- **Citation**: Z. Liu, "Image Tampering Recognition Algorithm Based on Improved YOLOv5s," in IEEE Access, vol. 11, pp. 95114-95119, 2023, doi: 10.1109/ACCESS.2023.3311474.
- **Keywords**: Feature extraction, Image recognition, Neck, Prediction algorithms, Data augmentation, Object detection, Ethics, Biomedical image processing, Image tamper recognition, YOLOv5s, attention module, EIOU loss function

## Installation

To use this implementation, you need to follow these steps:

1. Clone the YOLOv5 model repository:
2. Install the required packages:
3. Install Roboflow:
4. Install ClearML for visualization:

## Dataset

The dataset used for this implementation is obtained from Roboflow Universe. You can find the dataset [here](https://universe.roboflow.com/pavan-kumar/forge-eq4rh).

- Total Images: 7257
  - Train: 5075
  - Valid: 1459
  - Test: 723

## Customization

To adapt the YOLOv5 architecture for image tampering recognition, the number of classes has been modified from 80 to 2 based on the dataset.

## Usage

1. **Training**: Use the provided dataset to train the YOLOv5 model. You can train the model using the following command:

2. **Evaluation**: After training, evaluate the model's performance using the validation dataset:

3. **Testing**: Finally, test the trained model using the test dataset:

Feel free to explore and modify the code to suit your specific requirements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
