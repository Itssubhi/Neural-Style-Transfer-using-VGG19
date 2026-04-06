Neural Style Transfer using Pretrained VGG19
 Project Overview
Neural Style Transfer (NST) is a deep learning technique that combines the **content of one image** with the **artistic style of another image** to generate a new stylized image.

This project implements Neural Style Transfer using a **pretrained VGG19 convolutional neural network**, which extracts content and style features from images and blends them using optimization techniques.

---

 Objective

The main objectives of this project are:

- Understand how **Convolutional Neural Networks (CNNs)** extract image features
- Apply **Neural Style Transfer** using pretrained models
- Generate artistic images from content and style inputs
- Learn **feature extraction using VGG19 layers**

---

 Model Used

### VGG19 (Pretrained Model)

This project uses the **VGG19** model pretrained on the **ImageNet dataset**.

**Why VGG19?**

- Deep architecture with 19 layers
- Strong feature extraction capability
- Widely used in computer vision tasks
- Pretrained weights improve performance

---

 How Neural Style Transfer Works

The Neural Style Transfer process consists of:
1️⃣ Content Extraction
- Extracts content features from the content image
- Uses deeper layers of VGG19

2️⃣ Style Extraction
- Extracts artistic style from the style image
- Uses multiple convolution layers
- Style representation is captured using **Gram Matrix**

3️⃣ Image Optimization
- Combines content loss and style loss
- Updates the generated image iteratively
- Produces final stylized output

Neural-Style-Transfer-VGG19/
│
├── images/
│ ├── content.jpg
│ ├── style.jpg
│ └── output.jpg
│
├── neural_style_transfer.py
├── requirements.txt
├── README.md


 Technologies Used

- Python
- PyTorch (or TensorFlow — update if needed)
- NumPy
- Matplotlib
- PIL (Python Imaging Library)
- Pretrained VGG19 Model


