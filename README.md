<h1>A Machine Learning Model to predict Heart Diseases with the help of Framingham Data Set</h1>

<h3>About the dataset:</h3>

<b>The dataset is publically available on the Kaggle website, and it is from an ongoing ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has 10-year risk of future coronary heart disease (CHD).The dataset provides the patients’ information. It includes over 4,240 records and 15 attributes.</b>
<br></br>
<hr></hr>
<h3>Attributes:</h3>
<hr></hr>
<ol><b>
    <li>sex: male(0) or female(1);(Nominal)</li > 
    <li>age: age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)</li >
    <li>currentSmoker: whether or not the patient is a current smoker (Nominal)</li >
    <li>cigsPerDay: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarretts, even half a           cigarette.)</li >
    <li>BPMeds: whether or not the patient was on blood pressure medication (Nominal)</li >
      <li>prevalentStroke: whether or not the patient had previously had a stroke (Nominal)</li >
      <li>prevalentHyp: whether or not the patient was hypertensive (Nominal)</li >
      <li>diabetes: whether or not the patient had diabetes (Nominal)</li >
      <li>totChol: total cholesterol level (Continuous)</li >
      <li>sysBP: systolic blood pressure (Continuous)</li >
      <li>diaBP: diastolic blood pressure (Continuous)</li >
      <li>BMI: Body Mass Index (Continuous)</li >
      <li>heartRate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number             of possible values.)</li >
      <li>glucose: glucose level (Continuous)</li >
      <li>10 year risk of coronary heart disease CHD (binary: “1”, means “Yes”, “0” means “No”) - Target Variable</li >
    </b>
  </ol>

<hr></hr>
<h2>Objective: Build a classification model that predicts heart disease in a subject.</h2>(note the target column to predict is 'TenYearCHD' where CHD = Coronary heart disease) 

<h3>Please do the following steps: 
<br></br>
<ul>
    <li>Read the file and display columns.</li>
    <li>Handle missing values, Outliers and Duplicate Data</li>
    <li>Calculate basic statistics of t<li>he data (count, mean, std, etc) and exploratory analysts and describe your observations.</li>
    <li>Select columns that will be pro<li>bably important to predict heart disease.</li>
    <li>If you remove columns explain why you removed those.</li>
    <li>Create training and testing sets (use 60% of the data for the training and reminder for testing).</li>
    <li>Build a machine learning model to predict TenYearCHD</li>
    <li>Evaluate the model (f1 score, Acuuracy, Precision ,Recall and Confusion Matrix)</li>
    <li>Conclude your findings (Model which is giving best f1 score and why)</li>

