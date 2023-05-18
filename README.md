# 🐶 Dog vs 🐱 Cat Classifier using Deep Learning

This repository contains a Dog vs Cat classifier implemented using deep learning techniques. The classifier is trained to distinguish between images of dogs and cats, allowing you to classify new images as either dogs or cats.

## Requirements

To run the Dog vs Cat classifier, you need the following dependencies:

- Python (3.6 or later) 🐍
- TensorFlow (2.0 or later) 🧠
- Keras (2.2.4 or later) 🖥️
- NumPy (1.16 or later) 🔢
- Matplotlib (3.0 or later) 📊
- OpenCV (3.4 or later) 🖼️

You can install these dependencies using pip by running the following command:

```bash
pip install tensorflow keras numpy matplotlib opencv-python
```

## Dataset

The classifier is trained on the popular Dog vs Cat dataset, which consists of thousands of labeled images of dogs and cats. The dataset can be downloaded from the Kaggle website: [https://www.kaggle.com/c/dogs-vs-cats/data](https://www.kaggle.com/c/dogs-vs-cats/data).


## Customization

If you want to customize the Dog vs Cat classifier, you can modify the following parameters in the `train.py` script:

- `IMAGE_SIZE`: The size of the input images. You can adjust this parameter to match the size of your dataset images.
- `BATCH_SIZE`: The number of images to process in each training batch. Adjust this parameter based on your available memory.
- `EPOCHS`: The number of training epochs. Increase this parameter to allow the model to train for more iterations.
- `LEARNING_RATE`: The learning rate for the optimizer. You can experiment with different values to improve training performance.

Feel free to explore other deep learning architectures, such as Convolutional Neural Networks (CNNs), and incorporate them into the classifier for better performance.

## Acknowledgments

The Dog vs Cat classifier is inspired by various deep learning tutorials and examples available online. Special thanks to the creators of the Dog vs Cat dataset for providing a valuable resource for this project.
