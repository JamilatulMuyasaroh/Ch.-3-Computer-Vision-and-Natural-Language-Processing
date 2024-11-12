# Ch.-3-Computer-Vision-and-Natural-Language-Processing

This repository features team-based assignments focused on **Computer Vision** and **Natural Language Processing (NLP)**, tackling real-world applications in **image quality enhancement**, **object detection**, and **tweet classification**. The tasks incorporate advanced techniques such as transfer learning and pretrained models, providing hands-on experience in solving practical challenges in these fields.

## Notebooks Overview

### Image Quality Enhancement (03_Tim_6_1.ipynb)

- **Objective**: Improve the visibility of low-light images using advanced pooling techniques and contrast enhancement.
- **Methods Used**: Grayscale and binary conversions, histogram analysis, Max and Min Pooling, and CLAHE (Contrast Limited Adaptive Histogram Equalization) for effective contrast adjustment in low-visibility images.

---

### Handwritten Digit Classification using Transfer Learning (03_Tim_6_2.ipynb)

- **Objective**: Apply transfer learning for handwritten digit recognition using pretrained models like **ResNet18**, **DenseNet121**, and **Vision Transformer (ViT)** on the **MNIST dataset**.
- **Key Steps**:
  - Modify input and output layers for MNIST compatibility.
  - Tune batch sizes and learning rates.
  - Selectively freeze layers to enhance model performance.
  - Train and validate the models, measuring accuracy and loss to assess classification success.

---

### Real-Time Object Detection with YOLOv5 (03_Tim_6_3.ipynb)

- **Objective**: Detect and classify objects in real-time within video streams, marking them with bounding boxes and labels.
- **Steps**:
  - Extract frames from live video.
  - Use **YOLOv5** to detect objects in each frame.
  - Monitor detection accuracy and frames per second (FPS) to ensure real-time efficiency.

---

### Disaster Tweet Classification with BERT (03_Tim_6_4.ipynb)

- **Objective**: Classify tweets related to disaster events, assisting in emergency response by filtering relevant social media content.
- **Methodology**:
  - Preprocess tweets by removing URLs and stopwords.
  - Tokenize text for **BERT** input.
  - Train and evaluate the BERT model for binary classification, with metrics highlighting its accuracy in identifying disaster-related tweets.

---

## Running the Notebooks

To run each notebook:

1. Open **Google Colab** and upload the necessary datasets.
2. Follow the step-by-step instructions within each notebook to install any required libraries and dependencies.
3. Execute each cell in sequence to reproduce the analysis, training, and results.

Each notebook guides users through practical implementations of **Computer Vision** and **NLP** techniques, showcasing how these methods address common challenges in **image processing** and **text classification**. Running and modifying these notebooks allows users to gain hands-on experience with real-world data and state-of-the-art models.

