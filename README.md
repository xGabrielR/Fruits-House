# Fruits House

![f_r](https://user-images.githubusercontent.com/75986085/156441251-4ed310d6-1753-404f-8802-424d26a21e6f.png)

<h2>0. Introduction</h2>
<p>Fruits House is a agroindustry in southern Brazil. The bussiness model consists in fruits plantations, collect, preparation and transport for all Brazil.</p>
<p>It has recently started some expansions in the area of technology requiring a new method of collecting and classifying fruits.</p>
Bussiness Model Parts:

1. **Fruits Plantation:**
The plantation field is currently extensive, having n km of plantation with the distribution of 131 fruits.

2. **Fruits Collect:**
In the plantation fields, have some people focusing your working on collect, its possible a complete harvest a year depending on the fruit and its characteristics, I see fruits that take longer to collect and other fruits that annual collection is possible.

3. **Fruits Preparation:**
Have some products can be making with fruits like cakes, juices, dried, frozen for making candy and juices, and much more.  

4. **Fruits Storange:**
There is a lot of technology and preparation for the storage of fruits, with care mainly with frozen fruits that need specific constructions to keep them at an ideal temperature.

5. **Fruits Transportation:**
Basically how fruits are distributed throughout Brazil.

<h2>1. Bussines Problem</h2>

<p>Scientific Application for Fruits Classification.</p>
<p>The CEO of the company called Fruits House, a fruit and vegetable distributor in the south of Brazil, requested at data analysts some more scientific way to classify fruits so that this more scientific model could be coupled to a drone that would travel across the entire region of agricultural planting of several areas of the company's production throughout the southern region.</p>

> *How i classify fruits without human presence?*

<h2>2. Solution Strategy & Assumptions</h2>
<h3>First CRISP Cycle</h3>
<ul>
  <dl>
    <dt>Data Pre Processing & Preparation.</dt>
      <dd>In a high resume, prepare data with Data Augmentation technique and load the data with data augmentation from folder.</dd>
    <dt>Fruits Classifier with Convolutional Network.</dt>
      <dd>I have created CNN Model from scratch for train & test on dataset.</dd>
  </dl>
</ul>

<h2>3. Data Pre-Processing</h2>

<p>Deep Learning basically is math, statistic and programming, to make model, need to transform categorical variables in numeric.</p>
<p>I used simple load of Tensorflow, he automatic prepare the dataset with data augmentation parameters that i chosen based on my experience.</p>

<h2>4. Convolutiona Neural Network</h2>
**What is a CNN ?**<br>
CNN is a variation of MLP Models, used on image classification, object detection and neural style transfer.
Having some unique layers with specific objective, conv2 layer detect edges, max pooling reduce the dataset, dropuot reduce the neural network nodes, stride is the step of convolutional layer, padding is the expand of image, and much other features.

<p>Personal Draw of One Conv Network i have inplemented on project.</p>

![handdraw_cnn](https://user-images.githubusercontent.com/75986085/156445324-4a502c70-e71b-476f-9bf4-e6796c9706ff.png)

<h2>5. Model Deployment</h2>
<p>Deploy with Streamlit application on cloud. In this version you send a image to classifier, and the model return a probability dataframe.</p>
<a href="https://share.streamlit.io/xgabrielr/fruits-app/main/fruits-classification.py">Streamlit App</a><br>
