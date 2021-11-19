# Fruits House
Fruits Classification with Deep Learning

![fruits house](https://user-images.githubusercontent.com/75986085/138163047-c8484b1e-c4e6-45d1-980d-fef433050d74.png)


<h2>1. Bussines Problem</h2>

<p>Scientific Application for Fruits Classification.</p>
<p>The CEO of the company called Fruits House, a fruit and vegetable distributor in the south of Brazil, requested at data analysts some more scientific way to classify fruits so that this more scientific model could be coupled to a drone that would travel across the entire region of agricultural planting of several areas of the company's production throughout the southern region.</p>

<h2>2. Solution Strategy & Assumptions</h2>
<h3>First CRISP Cycle</h3>
<ul>
  <dl>
    <dt>Data Pre Processing.</dt>
      <dd>First steps is transform label to numeric value & split dataset 50% for training & validation.</dd>
    <dt>Data Preparation.</dt>
      <dd>Second step is data preparation, in this step basically create tensorflow train & validation dataset.</dt>
      <dd>Simple way to reduce dimensionality of dataset.</dd>
    <dt>Fruits Classifier with Deep Learning.</dt>
      <dd>Used EfficientNetB3 in this first cycle with 0.66 accuracy.</dd>
  </dl>
</ul>

<h2>3. Data Pre-Processing</h2>

<p>Deep Learning basically is math, statistic and programming, to make model, need to transform categorical variables in numeric.</p>
<p>I used label encoder from sklearn.</p>

<h2>4. Data Preparation</h2>

<p>This step is create train & validation dataset for model.</p>
<ul>
  <li>Data Augmentation.</li>
  <li>Convert images and labels to tensorflow dataset.</li>
  <li>Data Augmentation in training dataset.</li>
</ul>

<h2>4.x EfficientNetB3</h2>
<p>Model used with other head.</p>
<a href="https://www.tensorflow.org/api_docs/python/tf/keras/applications/efficientnet/EfficientNetB3">Tensorflow EfficientNetB3</a>

<h2>5. Model Evaluation</h2>

<ul>
  <dl>
    <dt>Accuracy.</dt>
      <dd>In first Cycle, Accuracy: 0.668 %</dd>
  </dl>
</ul>

<h2>6. Second Cycle</h2>
<p>New Data Preparation & Model with accuracy > 90%.</p>

<h2>Model Deploy</h2>
<p>Deploy with Streamlit</p>
<a href="https://share.streamlit.io/xgabrielr/fruits-app/main/fruits-classification.py">Streamlit App</a><br>
