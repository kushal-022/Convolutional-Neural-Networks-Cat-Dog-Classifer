<h1 align="center">
  ![Unknown](https://user-images.githubusercontent.com/105519854/227733154-9df08da0-c655-40f9-bdb1-2f24d930ddb6.jpeg)


</h1>

<p align="center">
  <strong>Convolutional Neural Networks for Cat Dog Recognition</strong><br>
  A deep learning model to classify images of cats and dogs with high accuracy.
</p>

<p align="center">
  <a href="#about">About</a> •
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#license">License</a>
</p>

---

## 🐾 About

This Cat Dog Recognition System is a deep learning model that uses Convolutional Neural Networks (CNNs) to classify images of cats and dogs. With a high accuracy of over 95%, this model can be used in various applications, including pet recognition systems and animal behavior studies.

The model was trained on a dataset of over 25,000 images of cats and dogs, with a balanced distribution of both classes. It consists of several convolutional and pooling layers, followed by fully connected layers and a softmax activation function for classification.

## 🚀 Installation

To use this Cat Dog Recognition System, follow these steps:

1. Clone this repository to your local machine using `git clone https://github.com/your_username/cat-dog-recognition.git`.
2. Install the required packages using `pip install -r requirements.txt`.
3. Download the pre-trained weights file from `https://drive.google.com/file/d/your_file_id/view` and place it in the `models` directory.

## 📈 Usage

To use the Cat Dog Recognition System, follow these steps:

1. Open the `predict.py` file in your text editor.
2. Update the `image_path` variable with the path to your cat or dog image.
3. Run the `predict.py` file using `python predict.py`.
4. The system will output the predicted class for your image (either "Cat" or "Dog") along with the probability score.

```bash
$ python predict.py
The image is a cat with probability 0.987.
