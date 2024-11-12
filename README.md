# Assignment 3: Computer Vision & Natural Language Processing

## Question 1  

**Category**: Computer Vision - Digital Image Processing  
**Case**:  

As of July 2023, Apple and Samsung lead the global smartphone market, holding a combined 52.61% market share. A critical feature of modern smartphones is their ability to capture high-quality photos in low-light conditions.  

- **Apple's Technology**:  
  In September 2019, Apple introduced Deep Fusion (iPhone 11 series) to enhance low-light photography. The Photonic Engine, an improved version, was launched in September 2022 with the iPhone 14 series.  

- **Samsung's Technology**:  
  In February 2023, Samsung released the Adaptive Tetra-squared Pixel Sensor with the Galaxy S23 series, promising exceptional bright photos from dark scenes.  

Both technologies employ Max Pooling to combine adjacent pixels into a single pixel, brightening dark images.  

**Task**:  
Replicate the pixel combining concept to enhance low-light photos and compare the results with the Contrast Limited Adaptive Histogram Equalization (CLAHE) method.  

---

## Question 2  

**Category**: Computer Vision - Transfer Learning with Pre-trained CNN  

**Case**:  

A new robotics facility in East Kalimantan, near Indonesia’s new capital (IKN) zero point, has tasked you with developing a Computer Vision model for their latest robot prototype. The robot must learn to recognize sequences of digits (0-9). With the prototype announcement deadline moved up, you have less than a week to complete the task.  

Leveraging Transfer Learning, you can quickly build an efficient solution using pre-trained models. The Modified National Institute of Standards and Technology (MNIST) database, containing grayscale handwritten digits, will serve as your dataset.  

**Task**:  
1. **Initial Model Selection**: Use DenseNet as the first model. Modify the number of neurons in the first and last layers to fit MNIST's 10 classes.  
2. **Training**: Set hyperparameters and train the model from scratch.  
3. **Performance Visualization**: Plot training and validation performance.  
4. **Layer Freezing Experiments**:  
   - Freeze "denseblock1" in one model.  
   - Freeze both "denseblock1" and "denseblock2" in another model.  
   - Retrain and compare performance for both models.  
5. **BONUS**: Replicate all steps using other models such as ResNet and Vision Transformer (ViT).  

---

## Question 3  

**Category**: Computer Vision - Real-time Object Detection  

**Task**:  

1. **Test YOLOv5 Accuracy**:  
   - Use the three provided YouTube URLs to test the accuracy of the YOLOv5 model in real-time object detection.  

2. **Answer Questions**:  
   - Answer the questions directly in the notebook, if any are provided.  

3. **Activate T4 GPU in Google Colab**:  
   - Enable T4 GPU in Google Colab if instructed to do so.  

---

## Question 4  

**Category**: Natural Language Processing - Text Classification  

**Case**:  

With the widespread availability of smartphones, people can report real-time emergency events on Platform X (formerly Twitter). This has led disaster relief organizations and news agencies to become increasingly interested in systematically monitoring Platform X.  

As an AI Scientist, you are tasked with classifying disaster tweets, specifically determining whether a tweet on Platform X is an indirect report about a disaster. To solve this, you can use the BERT (Bidirectional Encoder Representations for Transformers) model.  

By implementing fine-tuning techniques, the model you build can provide several benefits for future applications, including:  
- Analyzing communication patterns and public responses during emergencies.  
- Developing a Twitter-based early warning system.  
- Assisting disaster relief organizations in optimizing their responses.  
- Investigating the impact of social media on public perception of disasters.  
