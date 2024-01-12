<h1>Plant Disease Recognition Project</h1>
<h2>Overview</h2
This project focuses on the recognition of plant diseases using machine learning techniques. The dataset consists of images categorized into three classes: Healthy, Powdery Mildew, and Rust. The goal is to build a model capable of accurately classifying these images and aiding in the early detection of plant diseases.

<h2>Dataset</h2>
The dataset is divided into three sets: Training, Testing, and Validation. The distribution of images in each category is as follows:

<h2>Training Set</h2>
Healthy: 458 images
Powdery: 430 images
Rust: 434 images
Total: 1322 images

<h2>Testing Set</h2>
Healthy: 50 images
Powdery: 50 images
Rust: 50 images
Total: 150 images

<h2>Validation Set</h2>
Healthy: 20 images
Powdery: 20 images
Rust: 20 images
Total: 60 images
Note: The dataset comprises a total of 1322 samples used for training the machine learning model.

<h2>Model Performance</h2>
The developed model achieved an impressive accuracy of 92% on the provided dataset. The accuracy metric indicates the model's ability to correctly classify images into their respective categories, showcasing its effectiveness in plant disease recognition.

<h2>How to Use the Model</h2>
To utilize the trained model for plant disease recognition, follow these steps:

<h2>Clone the Repository:</h2>
<h3>Copy code</h3>
git clone https://github.com/vedchaudhari/plant-disease-recognition.git
cd plant-disease-recognition
Install Dependencies:

Copy code
pip install -r requirements.txt

<h2>Interpret Results:</h2>
The script will output the predicted class and confidence score for the given image.

<h2>Model Evaluation</h2>
If you wish to evaluate the model on a new dataset or make improvements, you can use the provided Jupyter notebook (model_evaluation.ipynb). This notebook contains the code for model evaluation, including accuracy, precision, recall, and F1 score.


