## notebooks

- __Using Grad-CAM for Lesion Localization in BI-RADS Classification with Deep Neural Networks__  
  This notebook demonstrates the application of [Grad-CAM](https://qudata.com/en/blog/seeing-through-ais-eyes-the-grad-cam-technique/) (_Gradient-weighted Class Activation Mapping_) on a deep neural network trained for Breast Imaging Reporting and Data System (BI-RADS) classification. BI-RADS is a standardized system used by radiologists to categorize findings in mammograms. In addition to classifying BI-RADS categories, we aim to visualize and localize areas within the mammogram that contribute most significantly to the network's decision-making process.

- __Transforming Raw Pixel Data of Mammograms A Step-by-Step Guide__  
  DICOM mammogram images are commonly encoded with pixel depths ranging from 8 to 16 bits, providing a broad spectrum of approximately 256 to 65,536 shades of gray. However, in the context of training deep neural networks standardization is paramount. To ensure uniformity and compatibility across all mammographic data, it is essential to convert these images to an 8-bit format. This guide outlines the steps to convert DICOM mammograms from their original 8–16 bit depth to an 8-bit format, addressing the imperative need for standardization in the training of deep neural networks for mammographic data.

- __Converting Greyscale DICOM to RGB for Bounding Box__  
  In medical imaging, particularly when working with DICOM files, adding annotations like bounding boxes can be crucial for enhancing the interpretability of images, aiding in diagnostic processes, and facilitating communication between healthcare professionals. However, traditional DICOM images are often grayscale, and directly overlaying annotations on them can be challenging.
This notebook addresses this challenge by guiding you through the process of converting grayscale DICOM images to RGB format.
