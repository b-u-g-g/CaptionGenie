# CaptionGenie



This system creates detailed, accurate descriptions for images by combining powerful image and text models. It’s built with PyTorch, which allows for fast processing and flexible model development.

### Key Features
- **Real-time Object Detection with YOLOv8**
  - *Why YOLOv8?* Known for being fast and precise, making it perfect for real-time use.
  - *What it does*: Finds objects in an image, giving essential information for captioning.

- **Feature Extraction using ResNet**
  - *Why ResNet?* Extracts detailed visual features, capturing what’s happening in the image.
  - *What it does*: Adds depth to the system’s understanding of the image, beyond just spotting objects.

- **Text Embeddings with BERT**
  - *Why BERT?* Good at understanding context, which helps in turning object labels into meaningful text.
  - *What it does*: Converts labels into context-rich text representations, making captions more accurate.

- **Caption Generation with T5 Transformer**
  - *Why T5?* Known for creating natural, readable sentences.
  - *What it does*: Turns image details and labels into full sentences, resulting in smooth, human-like captions.

### Technical Details
- **Powered by PyTorch**: For flexible, efficient development with GPU acceleration.
- **Custom DataLoader**: Speeds up data processing during training.
- **Adam Optimizer**: Helps the model learn quickly and effectively.

### Possible Uses
- Accessibility tools
- Content creation
- Social media


 


![Screenshot 2024-11-12 204855](https://github.com/user-attachments/assets/1fe8556d-d5ef-4a54-bcad-35930246c934)

![Screenshot 2024-11-12 210622](https://github.com/user-attachments/assets/cfe1a9f0-6331-4716-a37e-ac05e57dd535)

![Screenshot 2024-11-12 210731](https://github.com/user-attachments/assets/0e7af293-835a-4dd1-8373-19f5645bfdec)



