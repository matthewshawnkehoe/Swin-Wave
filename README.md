# Swin-Wave
A PyTorch implementation of the Swin Transformer for image processing.

## Description
The Swin Transformer serves as a versatile framework for computer vision and is built upon combining features from Convnets and the Vision transformer. We train multiple models using the Swin transformer.

## Usage
1. **Clone the repository:**
    ```bash
    git clone https://github.com/matthewshawnkehoe/Swin-Wave.git
2. **Navigate to the repository directory and install the required packages:**
   ```bash
   pip install -r requirements.txt


## License
This project is licensed under the MIT License.

## Acknowledgements
The Swin Transformer model is based on the paper "Swin Transformer: Hierarchical Vision Transformer using Shifted Windows" by Ze Liu, Yutong Lin, Yue Cao, Han Hu, Yixuan Wei, Zheng Zhang, Stephen Lin, and Baining Guo.

Paper: Swin Transformer: Hierarchical Vision Transformer using Shifted Windows

Link: [arXiv:2103.14030](https://arxiv.org/abs/2103.14030)
Summary: The Swin Transformer serves as a general-purpose backbone for computer vision. Challenges in adapting Transformer from language to vision arise from differences between the two domains, such as large variations in the scale of visual entities and the high resolution of pixels in images compared to words in text. To address these differences, the authors propose a hierarchical Transformer whose representation is computed with Shifted windows. The shifted windowing scheme brings greater efficiency by limiting self-attention computation to non-overlapping local windows while also allowing for cross-window connection.
This hierarchical architecture has the flexibility to model at various scales and has linear computational complexity with respect to image size. These qualities of Swin Transformer make it compatible with a broad range of vision tasks, including  image classification and dense prediction tasks such as object detection and semantic segmentation.
