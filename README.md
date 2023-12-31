<h1>Rock, Paper, Scissors Classifier</h1>
<h2>Overview</h2>
<p>This repository contains a program for training a Rock, Paper, Scissors image classifier using TensorFlow and Keras. The program utilizes a convolutional neural network (CNN) to classify images of rock, paper, and scissors gestures. The dataset used for training is obtained from the Dicoding Academy's Rock, Paper, Scissors dataset.</p>
<h2>Prerequisites</h2>
<p>Before running the program, ensure that you have the following dependencies installed:</p>

<ul>
<li>TensorFlow</li>
<li>Keras</li>
<li>Matplotlib</li>
<li>Numpy</li>
<li>Google Colab (if running on Google Colab)</li>
</ul>

<p>Install the dependencies using the following command:</p>
<code>pip install tensorflow keras matplotlib numpy</code>

<h2>Dataset</h2>
<p>The dataset used in this project is available from the Dicoding Academy. It consists of images of rock, paper, and scissors gestures. The dataset is automatically downloaded and extracted during the execution of the program.</p>

<h2>Data Augmentation</h2>
<p>Data augmentation is applied during the training process to enhance the model's performance. Augmentation techniques include rotation, brightness adjustment, shear, zoom, and horizontal flip.</p>

<h2>Model Architecture</h2>
<p>The neural network model is built using the Sequential API of Keras. It consists of convolutional layers, max-pooling layers, a flattening layer, dropout for regularization, and fully connected layers. The output layer uses the softmax activation function to predict the class probabilities.</p>

<h2>Training</h2>
<p>The model is trained using the training dataset, and validation is performed on a subset of the dataset. The training process is monitored using callbacks, including a learning rate scheduler and a custom callback to stop training when both training and validation accuracy exceed a specified threshold.</p>

<h2>Visualization</h2>
<p>Training and validation accuracy, as well as loss, are visualized using Matplotlib to assess the model's performance over epochs.</p>

<h2>Prediction</h2>
<p>The trained model can make predictions on new images uploaded by the user. The user can upload an image, and the program will display the predicted class (rock, paper, or scissors) along with the confidence scores.</p>

<h2>Usage</h2>
<p>To run the program, execute the provided Python script in a compatible environment. If using Google Colab, ensure that the required libraries are installed and execute the script in a Colab notebook.</p>

<code>python rock_paper_scissors_classifier.py</code>

<h2>Acknowledgments</h2>
<ul>
<li>Dicoding Academy for providing the Rock, Paper, Scissors dataset.</li>
<li>TensorFlow and Keras communities for their powerful tools and resources.</li>
</ul>

<p>Feel free to contribute, report issues, or suggest improvements to enhance the classifier!</p>
