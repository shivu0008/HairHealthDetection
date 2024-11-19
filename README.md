# Hair Health Prediction

## Description
This project involves predicting the health of hair based on image inputs, utilizing machine learning models for hair loss detection. The model classifies images of individuals into different stages of hair health, from normal to various stages of hair loss.

The project uses a Convolutional Neural Network (CNN) and the VGG16 pre-trained model to achieve high accuracy. The model is integrated with a GUI built using Tkinter for user-friendly interaction, allowing users to upload images and receive predictions on their hair health status.

### Features:
- **Image Classification**: Classifies images of individuals into different hair loss types.
- **User Interface**: A Tkinter-based GUI to upload images and view predictions.
- **Prediction and Advice**: Displays predictions and provides specific advice for each hair health type.

## Installation

### Requirements:
- Python 3.x
- TensorFlow
- OpenCV
- scikit-learn
- Pillow
- tkinter
- numpy

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Hair-Health-Prediction.git
   cd Hair-Health-Prediction

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```
3. Download or upload your dataset (images of individuals) and save them in the images/ folder.

4. Run the application:

```bash
python app.py
```

Usage
Once the application starts:

Upload an image using the 'Upload Image' button.
Click the 'Predict Hair Loss' button to get the prediction of your hair health.
View the prediction along with specific advice related to your hair health.

Model Overview
The model used in this project is based on a Convolutional Neural Network (CNN) architecture and fine-tuned with VGG16. The model was trained on a dataset of hair health images and classified into 7 different types, ranging from normal hair to various stages of hair loss.

Model Architecture:
Conv2D layers for feature extraction.
MaxPooling layers for dimensionality reduction.
Dense layers for classification.

Contributions
Feel free to contribute by submitting issues or pull requests. This project is open for improvements, whether it's enhancing the model's accuracy or improving the user interface.

Contact
For any queries, feel free to reach out via email at:
Email: kshivanshu.k@gmail.com
LinkedIn: https://www.linkedin.com/in/shivanshu-kumar1306/

