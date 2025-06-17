````markdown
# Image Classification Project

A convolutional neural network built in Google Colab to classify images into 10 categories. Leveraging a MobileNetV2 backbone with transfer learning, this model achieves **91% validation accuracy** in under 20 epochs.

## 🔧 Tech Stack

- **TensorFlow & Keras**  
- **Google Colab** environment  
- **tf.data** for data loading & augmentation  

## 🚀 Getting Started

1. Open the notebook in Colab:  
   [Image_Classification_Project.ipynb](Image_Classification_Project.ipynb)  
2. Install dependencies & mount Drive:
   ```python
   !pip install tensorflow
   from google.colab import drive
   drive.mount('/content/drive')
````

3. Run all cells to preprocess, train, and validate.

## 📈 Results

* **Train Acc:** 94.5%
* **Val Acc:** 91.0%
* Inference at \~200 images/sec on a Tesla T4.

```

> Copy and paste the above into your `image-classification-project/README.md`.
```
