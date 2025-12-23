A-  one step is dataset :
    -This project focuses on building a complete Computer Vision pipeline, starting from data collection to training deep learning models for both image classification and object detection tasks.
     The dataset was manually collected and consists of 10 different color classes, representing diverse visual patterns under varying conditions. The data collection process was designed to ensure class balanceand      visual diversity to improve model generalization.

      link dataset :https://github.com/bongaaaaA/datasets/blob/main/Color%20Recognition.rar

      ![WhatsApp Image 2025-12-23 at 9 23 48 PM](https://github.com/user-attachments/assets/5cb74fdc-8b06-47a6-a1a4-d5151ccbfa68)
B-  model CNN WITH VGG19
    This project presents a Convolutional Neural Network (CNN)–based approach for color classification using a VGG19 architecture implemented with PyTorch. The model is trained to classify images into 10 distinct       color classes, focusing on learning robust visual features from RGB images.
    The dataset consists of labeled color images, which were preprocessed through resizing, normalization, and data augmentation to improve generalization and reduce overfitting. A pre-trained VGG19 model was           utilized as a backbone, leveraging transfer learning to benefit from features learned on large-scale image datasets. The final fully connected layers were customized to match the 10-color classification task.
    link nootbook in kaggle :https://www.kaggle.com/code/abdelrahmanaboelnaga/graduation-progect-cnn-with-vgg19


c-  object detection model :

   This project implements an object detection and color recognition system using the YOLO (You Only Look Once) framework. The model is designed to detect objects in real time and accurately identify the color    present at a specific point of interest within the detected region.
The system processes input images or video frames using a YOLO-based detection pipeline to localize objects efficiently. After detecting the target object, the pixel values at a predefined point (or a dynamically selected point) inside the bounding box are analyzed to determine the corresponding color. This approach enables precise color extraction while maintaining high inference speed.
The model leverages YOLO’s single-stage detection architecture, allowing for fast and reliable performance suitable for real-time applications. The color classification process is integrated seamlessly with the detection output, providing both spatial localization and color information in a single pipeline.
This project demonstrates a practical use case of combining object detection and pixel-level color analysis, making it suitable for applications such as industrial inspection, visual tracking, robotics, and computer vision–based color sensing systems.

video run: 

https://github.com/user-attachments/assets/399b98b4-926e-4eaa-a98c-a6541c6c873c




