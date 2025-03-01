<div align="center">
    <h1>Multimodal Sarcasm Detection</h1>
</div>

## **Introduction**

This repository aims to classify an image and its corresponding caption into one of four categories: not-sarcasm, image-sarcasm, text-sarcasm, or multi-sarcasm. To extract features, I use transformer-based architectures: ViT for image features and Jina for text features, along with EasyOCR to extract text appearing within the image. The complete pipeline is presented below: 

