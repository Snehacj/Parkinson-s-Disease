<html>
  <head>
    <h1>PARKINSON'S DISEASE - MACHINE LEARNING MODELS</h1>
    <b>-Built model to predict if a person has parkinson's disease or not</b>
  </head>
  <hr/>
  <body>
    <img src="https://www.quickobook.com/uploads/media/5fd4697dec75b.jpg" height="85%" width="85%" alt=""/>
  <h1>Overview</h1>
  Parkinson's disease is a brain disorder that causes unintended or uncontrollable movements, such as shaking, stiffness, and difficulty with balance and coordination. Symptoms usually begin gradually and worsen over time. As the disease progresses, people may have difficulty walking and talking.The main risk factor is age, because Parkinson's disease is most commonly found in adults over the age of 50 (although diagnoses can occur in much younger people). Men also have a higher risk of Parkinson's disease than women.
  <h1>Acknowledgement :</h1>
  This Datset is taken from Kaggle
  <h1>Dataset :</h1>
     <a href="https://www.kaggle.com/datasets/nidaguler/parkinsons-data-set"><br/>https://www.kaggle.com/datasets/nidaguler/parkinsons-data-set</a>
  <h2>
    Dataset details
  </h2>
  <p1>
  <table>
  <tr>
    <th>Field</th>
    <th>Description</th>
    
  </tr>
  
  <tr>
    <td>name</td>
    <td>name and recording number of patients</td>
    
  </tr>
  <tr>
    <td>MDVP:Fo(Hz)</td>
    <td>Average vocal fundamental frequency</td>
    
  </tr>
  <tr>
    <td>MDVP:Fhi(Hz)</td>
    <td>Maximum vocal fundamental frequency</td>
    
  </tr>
  <tr>
    <td> MDVP:Flo(Hz)</td>
    <td> Minimum vocal fundamental frequency</td>
    
  </tr>
  <tr>
    <td>MDVP:Jitter(%)</td>
    
    
  </tr>
  <tr>
    <td>MDVP:Jitter(Abs)</td>
    
    
  </tr>
    
  <tr>
    <td>MDVP:RAP</td>
    
    
  </tr>
  <tr>
    <td>MDVP:PPQ</td>
    
    
  </tr>
  <tr>
    <td>Jitter:DDP</td>
    <td>Several measures of variation in fundamental frequency</td>
    
  </tr>
  <tr>
    <td>MDVP:Shimmer</td>
    
    
  </tr>
  <tr>
    <td>MDVP:Shimmer(dB)</td>
    
    
  </tr>
  <tr>
    <td>Shimmer:APQ3</td>
    
    
  </tr>
    
  <tr>
    <td>Shimmer:APQ5</td>
    
    
  </tr>
  

  <tr>
    <td>MDVP:APQ</td>
   
    
  </tr>
  
  <tr>
    <td>Shimmer:DDA</td>
    <td>Several measures of variation in amplitude</td>
    
  </tr>
  <tr>
    <td>NHR</td>
    
    
  </tr>
    
  <tr>
    <td>HNR</td>
    <td>Two measures of ratio of noise to tonal components in the voice</td>
    
  </tr>
 
  <tr>
    <td>status</td>
    <td>Health status of the subject (one) - Parkinson's, (zero) - healthy</td>
    
  </tr>
  
  <tr>
    <td>RPDE</td>
    
    
  </tr>
  
  <tr>
    <td>D2 </td>
    <td>Two nonlinear dynamical complexity measures</td>
    
  </tr>
  
  <tr>
    <td>DFA</td>
    <td>Signal fractal scaling exponent</td>
    
  </tr>
  
  <tr>
    <td>spread1</td>
   
    
  </tr>
  
  <tr>
    <td>spread2</td>
    
    
  </tr>
  
  
  <tr>
    <td>PPE</td>
    <td>Three nonlinear measures of fundamental frequency variation</td>
    
  </tr>
    
  </table>
  </p1>
  
  
  <h2>
    Problem Statement:
  </h2>
  <p1>
     This dataset collected from  patients.Based on the symptoms the parkinson's disease is classfied into different categories. The objective is to apply machine learning techniques on this data and predict parkinson's categories from features.
  </p1>
  
 <h2>
    Implementation
  </h2>
 <p1>
 Libraries<br>
 <ul>
  <li>NumPy</li>
  <li>Pandas</li>
  <li>Sklearn</li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
</ul>
</p1>
 <h2>
    Table of Content
  </h2>
 <p1>
 <ul>
  <li>Importing libraries</li>
  <li>Reading data</li>
  <li>Cleaning data</li>
  <li>Exploring data</li>
  <li>Extracting data</li>
  <li>Visualising data</li>
  <li>Creating models</li>
  <li>Conclusion</li>
</ul>
</p1>   
  
 
 
  <h2>
   ML Approach
  </h2>
  <p1>
The aim is to create a model that helps the users to apply machine learning approach to predict the parkinson's disease have or not. Here, the models used are
<ul>
  <li>Logistic Regression</li>
  <li>Naive Bayes</li>
  <li>KNN</li>
  <li>Random Forest</li>
</ul>
  </p1>
  <h2>
    ML Approach Functions
  </h2>
 <p1>
 <ul>
  <li>Model fitting</li>
  <li>Predicting using model</li>
  <li>Accuracy score</li>
  <li>Confusion matrix</li>
  <li>Classification Report</li>
</ul>
</p1>   
  
 
  
 <h2>   
  Conclusion
 </h2>
<p1>
  <table>
  <tr>
    <th>Model</th>
    <th>Accuracy</th>
    
    
  </tr>
  <tr>
    <td>Logistic Regression</td>
    <td>82%</td>
   
    
  </tr>
 
  <tr>
    <td>Random Forest</td>
    <td>92%</td>
    
    
  </tr>
  <tr>
    <td>SVM</td>
    <td>82%</td>
   
    
  </tr>
  <tr>
    <td>KNN</td>
    <td>79%</td>
   
    
  </tr>
  
  </table>
  <ul>
  <li>
  Comparing Random Forest is the best from among the models trained to predict the accurate result with an accuracy of 92%.
  </ul>
  </li>

</p1> 


</html>
 
  
</body>
  </html>

