# Flower-Type-Detection-with-CNN

<h1>Flower Image Classification using Convolutional Neural Networks</h1>

<h2>Overview</h2>
<ul>
    <li>This project focuses on classifying flower images into different categories using Convolutional Neural Networks (CNNs).</li>
    <li>The implementation is done in Python, making use of various machine learning libraries.</li>
</ul>

<h2>Project Workflow</h2>

<h3>Data Preparation</h3>
<ul>
    <li>The project begins with the preparation of the image dataset, which is located in the 'dataset/train' directory.</li>
    <li>Flower images of various types (daisy, sunflower, tulip, dandelion, rose) are loaded and resized to a consistent size of 150x150 pixels.</li>
    <li>These images are then stored in a list (<code>X</code>), while their corresponding labels (flower types) are stored in another list (<code>Z</code>).</li>
</ul>

<h3>Data Processing</h3>
<ul>
    <li>Labels undergo encoding into numerical values using the <code>LabelEncoder</code> and one-hot encoding techniques.</li>
    <li>The dataset is divided into training and validation sets using the <code>train_test_split</code> function.</li>
</ul>

<h3>Model Building</h3>
<ul>
    <li>A Convolutional Neural Network (CNN) model is constructed using the Keras deep learning framework.</li>
    <li>The CNN architecture comprises convolutional layers, max-pooling layers, and fully connected layers.</li>
</ul>

<h3>Model Training</h3>
<ul>
    <li>The model is compiled and trained using the training dataset.</li>
    <li>Data augmentation techniques are applied to prevent overfitting.</li>
    <li>Learning rate reduction is employed to fine-tune the model during training.</li>
</ul>

<h3>Model Evaluation</h3>
<ul>
    <li>Visualizations of loss and accuracy curves are generated to assess the model's performance during the training process.</li>
</ul>

<h3>Prediction and Visualization</h3>
<ul>
    <li>The trained model is utilized to make predictions on a validation dataset.</li>
    <li>Random images are displayed along with their predicted and actual labels.</li>
    <li>Properly classified and misclassified images are showcased for visual inspection.</li>
</ul>

<h2>Usage</h2>
<ol>
    <li>Clone this repository.</li>
    <li>Ensure that you have the required Python libraries installed.</li>
    <li>Execute the provided Python script to train the model and perform flower image classification.</li>
</ol>

<h2>Results</h2>
<ul>
    <li>The primary objective is to achieve high accuracy in the classification of flower images into their respective categories.</li>
    <li>The model's performance can be evaluated by examining the loss and accuracy curves and by inspecting correctly and incorrectly classified images.</li>
</ul>

<h2>Conclusion</h2>
<ul>
    <li>This project serves as an illustration of the practical application of Convolutional Neural Networks for image classification tasks.</li>
    <li>It can serve as a foundational example for similar projects involving image classification and deep learning.</li>
</ul>
