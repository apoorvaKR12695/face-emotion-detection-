
</p>
<h1 align="center"> Face Emotion Detection </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>



![1_kNmSTa-xG_Ed_xmHPWAzeQ](https://user-images.githubusercontent.com/102009481/177730708-9d7f518e-0553-47b0-8d77-7d3be8159d56.png)

<p>Built an  face emotion detection app that detects the sentiment of the online classroom using live video from the webcam and real-time aggregated feedback to the instructors about the class using CNN model and deployed on Heroku platform.</p>

<h2> :floppy_disk: Project Files Description</h2>


<p>This Project includes 2 executable files, 2 text files ,1 h5 file as well as 2 directories as follows:</p>
<h4>Executable Files:</h4>
<ul>
  
  <li><b>train.py</b> - Includes all functions required for classification operations  and generates the model.h5 file after execution.</li>
  <li><b>test.py</b> -  after execution, evaluation is done on the unseen data as in confusion_matrix.txt.</li>
</ul>

<h4>Output Files:</h4>
<ul>
  <li><b>model.h5</b> - Model contains information about the emotions of the train set, such as the Happy,Sad,Disgust,Calm and so on.</li>
  <li><b>confusion_matrix.txt</b> - Contains information about the classified emotions of the test set.</li>
  <li><b>pics</b> - which contains the output of detecting emotions through live webcam.</li>
</ul>

<h4>Source Directories:</h4>
<ul>
  <li><b>train directory</b> - Includes all emotions  for the training phase of the program.</li>
  <li><b>test directory</b> - Includes all emotions for the testing phase of the program.</li>
</ul>

<h4>Files required to deploy on Heroku:</h4>
<ul>
  <li><b>Haarcascade_frontalface_alt.xml</b> -used for image processing.</li>
  <li><b>runtime.txt</b> - python environment.</li>
  <li><b>procfile</b> - Procfile is a mechanism for declaring what commands are run by your application’s dynos on the Heroku platform..</li>
  <li><b>setup.sh</b> - This file is necessary for Heroku to know which libraries it needs to run your application. .</li>
  <li><b>requirements.txt</b> - this file contains all the neccesarry dependencies .</li>
  
</ul>
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: CNN </h2>

<p> Convolutional Neural Networks (CNNs) are a type of Neural Network that has excelled in a number of contests involving Computer Vision and Image Processing.Designing the CNN model for, emotion detection .creating blocks using Conv2D layer,Batch-Normalization, Max-Pooling2D, Dropout, Flatten, and then stacking them together and at the end-use Dense Layer for output


![1_CnNorCR4Zdq7pVchdsRGyw](https://user-images.githubusercontent.com/102009481/177744968-d0bb6264-acd9-429e-bc7e-56cd3464574c.png)



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :clipboard: Execution Instruction</h2>
<p>The order of execution of the program files is as follows:</p>


<p><b>1) train.py</b></p>
<p>Then, the train.py file must be executed, to define all the functions and variables required for classification operations which leads to the production of the model.h5 file. 

<p><b>2) test.py</b></p>
<p>Finally, the test.py file must be executed to evaluate the model performance on unseen data.




  Deployment Link for Heroku -Deployment Link for heroku :- https://face-recognit-apoorva.herokuapp.com/

Deployment Link for Streamlit Share - https://share.streamlit.io/apoorvakr12695/face-emotion-recognition-/main/app.py

# Run WebApp Locally

Clone the project

        git clone https://github.com/apoorvaKR12695/face-emotion-recognition-

  
Install dependencies

          pip install -r requirement.txt
  
Start local webcam

           streamlit run app.py

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

< Apoorva KR > | Avid Learner | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

<p> <i> Contact me for Data Science Project Collaborations</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/almabetter/mycompany/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/orgs/AlmaBetter-School/)



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<h2> :books: References</h2>
<ul>
  <li><p>Jonathan Lee, 'Notes on Naive Bayes Classifiers for Spam Filtering'. [Online].</p>
      <p>Available: https://courses.cs.washington.edu/courses/cse312/18sp/lectures/naive-bayes/naivebayesnotes.pdf</p>
  </li>
  <li><p>Wikipedia.org, 'Naive Bayes Classifier'. [Online].</p>
      <p>Available: https://en.wikipedia.org/wiki/Naive_Bayes_classifier</p>
  </li>
  <li><p>Youtube.com, 'Naive Bayes for Spam Detection'. [Online].</p>
      <p>Available: https://www.youtube.com/watch?v=8aZNAmWKGfs</p>
  </li>
  <li><p>Youtube.com, 'Text Classification Using Naive Bayes'. [Online].</p>
      <p>Available: https://www.youtube.com/watch?v=EGKeC2S44Rs</p>
  </li>
  <li><p>Manisha-sirsat.blogspot.com, 'What is Confusion Matrix and Advanced Classification Metrics?'. [Online].</p>
      <p>Available: https://manisha-sirsat.blogspot.com/2019/04/confusion-matrix.html</p>
  </li>
  <li><p>Pythonforengineers.com, 'Build a Spam Filter'. [Online].</p>
      <p>Available: https://www.pythonforengineers.com/build-a-spam-filter/</p>
  </li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)











