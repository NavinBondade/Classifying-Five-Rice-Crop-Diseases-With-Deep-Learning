# Classifying Five Rice Crop Diseases With Deep Learning
<p align="center">
<a href="https://nbviewer.jupyter.org/github/NavinBondade/Classifying-Five-Rice-Crop-Diseases-With-Deep-Learning/blob/main/Rice%20Diseases%20Classification%20and%20Prediction/Notebook/Rice_Leaf_Diseases_Classification_and_Prediction_92_accuracy.ipynb" target="_blank">
  <img align="center"  src="https://github.com/NavinBondade/Distinguishing-Fake-And-Real-News-With-Deep-Learning/blob/main/Graphs/button_if-github-fails-to-load-the-notebook-click-here%20(4).png?raw=true"/>
</a>
</p>


<p align="center">
<a href="https://ricediseasesnavin.herokuapp.com/"  target = "_blank">
  <img align="center"  src="https://github.com/NavinBondade/Identifying-Nine-Tomato-Disease-With-Deep-Learning/blob/main/Tomato%20Disease%20and%20Classification/Graphs%20and%20Pictures/webappbtn.png" height="50" />
</a>
</p>

<img src="https://image.freepik.com/free-photo/rice-blast-disease-rice-diseases-damage-rice-grains-paddy-farms_46178-489.jpg" alt="tomato" width="1000" height="510">
<p>Rice is an inseparable part of Indian's diet, and that's why India every year produces a whopping 104.80 million tonnes of rice. Rice is counted as one of the most labor-intensive crops to grow. Rice crops often suffer from soil moisture stress due to erratic, inadequate rainfall, and other environmental factors. These many times give rise to the spread of diseases which badly damage the crop fields and cause wastage of money and time to farmers too. To battle against this problem and provide farmers a cheaper and faster means of understanding the crop diseases I have created a deep learning model that capable of identifying five rice diseases.</b></p> 
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Keras</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Numpy</li>
  <li>Glob</li>
</ul>
<h2>Data Visualization</h2>
<img src="https://github.com/NavinBondade/Rice-Leaf-Diseases-Detection-And-Classification/blob/main/Rice%20Diseases%20Classification%20and%20Prediction/Pictures/5%20Rice%20Diseases%20v2.png?raw=true" alt="rice" >
<h2>Model Detail</h2>
<p>The deep learning model at its core uses four convolutional neural network layers followed by Max pooling layers for recognizing the rice diseases, it also uses three dense layers for decision making. All the layers use RELU as an activation function except the last dense layer that uses the softmax activation function. </p>
<h2>Model Training</h2>
<ul>
  <li><h3>Loss<h3></li>
</ul>
<img src="https://github.com/NavinBondade/Rice-Leaf-Diseases-Detection-And-Classification/blob/main/Rice%20Diseases%20Classification%20and%20Prediction/Graph/loss.png" width="450" height="300">
<ul>
  <li><h3>Accuracy<h3></li>
</ul>
<img src="https://github.com/NavinBondade/Rice-Leaf-Diseases-Detection-And-Classification/blob/main/Rice%20Diseases%20Classification%20and%20Prediction/Graph/accuracy.png" width="450" height="300">
<p>The model was trained for 10 epochs. During training, the model uses Adam as an optimizer and uses categorical cross-entropy as the loss function. The model has trained perfectly and is free from overfitting or underfitting.</p>    
<h2>Model Evaluation</h2>
<ul>
  <li><b>Training Data Accuracy: 93 %</b></li>
  <li><b>Test Data Accuracy: 92 %</b></li>
  <li><b>Training Data Loss: 0.18</b></li> 
  <li><b>Test Data Loss: 0.19</b></li> 
</ul>  
<h2>Model Prediction</h2>
<img src="https://github.com/NavinBondade/Rice-Leaf-Diseases-Detection-And-Classification/blob/main/Rice%20Diseases%20Classification%20and%20Prediction/Pictures/5%20Rice%20Diseases%20Prediction.png">
<p>During the model testing phase, the model has predicted all the five rice diseases i.e, Gudi Rotten, Apex Blast, Leaf Blast, Leaf Burn, Neck Blast Paddy with <b>100 percent accuracy.</b></p>  
<h2>Conclusion</h2>
<p>In this project, I have created deep convolutional neural network architecture for correctly identifying the five rice crop diseases with an accuracy of 92 percent. </p>    

