# ML-Web-App-Using-Streamlit and Python

Built interactive web applications with Streamlit and Python
<br><br>
Trained Logistic Regression, Random Forest, and Support Vector Classifiers using scikit-learn
<br><br>
Plot evaluation metrics for binary classification algorithms
<br><br>
## SVM 
A Support Vector Machine (SVM) is a discriminative classifier formally defined by a separating hyperplane. In other words, given labeled training data (supervised learning), the algorithm outputs an optimal hyperplane which categorizes new examples.

To understand SVM’s a bit better, Lets first take a look at why they are called support vector machines.  So say we got some sample data over here of features that classify whether a observed picture is a dog or a cat, so we can for example look at snout length or and ear geometry if we assume that dogs generally have longer snouts and cat have much more pointy ear shapes. 

So how do we decide where to draw our decision boundary? 
Well we can draw it over here or here or like this. Any of these would be fine, but what would be the best? If we do not have the optimal decision boundary we could incorrectly mis-classify a dog with a cat. So if we draw an arbitrary separation line and we use intuition to draw it somewhere between this data point for the dog class and this data point of the cat class. 

These points are known as support Vectors – Which are defined as data points that the margin pushes up against or points that are closest to the opposing class. So the algorithm basically implies that only support vector are important whereas other training examples are ‘ignorable’. An example of this is so that if you have our case of a dog that looks like a cat or cat that is groomed like a dog, we want our classifier to look at these extremes and set our margins based on these support vectors. 


