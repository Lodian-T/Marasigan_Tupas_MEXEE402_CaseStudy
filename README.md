# MexEE-402-Data-Preprocessing-Case-Study_Group10

MexEE Elective 2: Data Science and Machine Learning
Batangas State University, Alangilan Campus
1st Semester, AY 2026-2027

## 🧑‍🏭 Members

| Name | Student Number | Section |
|---|---|---|
| Marasigan, Alden | 23-07009 | MEXE-4101 |
| Tupas, Lodian | 23-05226 | MEXE-4101 |

## 📔 Notebook links

| Chapter | Marasigan, Alden | Tupas, Lodian |
|---|---|---|
| Ch1_2_3 | https://colab.research.google.com/drive/1tzEO2dmpvWIQXrWunWQff42qqUk2o4Px#scrollTo=eHF2OXY5GSQA | https://colab.research.google.com/drive/1hDRaNvftASBy8CAJiLMuqrbxUX-EBwag?usp=sharing |
| Ch4 | https://colab.research.google.com/drive/18QgJTsmmBEk_6jfOchyTuaR-hQE41Y37 | https://colab.research.google.com/drive/1mheLgayAMAX1K0D_F2K5BgwD8S7CiB9p?usp=sharing |
| Ch5 | https://colab.research.google.com/drive/1Kgh6saVi40ZGhKN8IIeNsnwBwBzGgU8t | https://colab.research.google.com/drive/1NoS3P4YnMir36r4Tj76VcIc_K0yIeXqq?usp=sharing |
| Ch6 | https://colab.research.google.com/drive/1jn6HjwaXqkk-dla-VaXMaMJHnA4x4YHw | https://colab.research.google.com/drive/1tNp55NRib7lng0xU6ixkh527-5YnbBDp?usp=sharing |
| Ch7 | https://colab.research.google.com/drive/1wuDjL4TOEyO4JqAs2AgNlrRk5U0zfdlN | https://colab.research.google.com/drive/1qZphFZbZprpsycKh8ARFSipCnk1W-aqo?usp=sharing |
| Ch8 | https://colab.research.google.com/drive/1hH0_JXB8Ek_nZV06YLkkmiPKDtpvQfu- | https://colab.research.google.com/drive/1dNoNIYaXNf0kbYrXHJnCraOySthx8vCC?usp=sharing |
| Ch9 | https://colab.research.google.com/drive/1IJDuS3jjPhR0f24ZLCy2Xde0GYXpPuF8 | https://colab.research.google.com/drive/1AQvy_E1JffBGqwEGHUQq4wxTomyqrsFP?usp=sharing |

## 🧠 What we learned

One short paragraph per chapter, Ch1_2_3 to Ch9. Say what the chapter taught
you and what surprised you. Not what the library does, but what you understood.

| Chapter | Student Learnings |
|---|--------------|
| Ch1_2_3 | Chapter 1, 2, and 3 is simply the introduction of the whole project. It is the starting point of producing outputs from processing raw data in a csv file. Essentially, it taught the students how to view the categorical titles and the numerical information of a certain data set. Additionallu, the students was curious on how data sets were managed and processed. This chapter mentioned data cleaning and included multiple methods on how to do so. It was very interesting and was a good start for the project. |
| Ch4 | Feature Engineering and Encoding was the main topic for Chapter 4. This chapter taught the students on how to produce or combine existing data to create new options or categories that we call Features. Aside from this, two types of encoding methods were mentioned, which is One-hot and Ordinal encoding. To familiarize themselves with these methods, the students identify One-hot as simply  producing new features that are solely based on qualitative or descriptive categories. While Ordinal focuses on data that has a natural order as well as numerical value. These concepts are the main learnings that the student gained from Chapter 4. |
| Ch5 | Chapter 5 focuses on Data Scaling and Normalization, these methods are quite essential in correlating data categories that are distanced from each other. Without scaling, data will have certain delays in terms of processing since there are no clear connections between the two categories being processed. To explain this even further, based on the notebook, Data scaling focuses on leveling fields or providing a standard range for data to be compared. As for normalization, similar to data scaling it manages data to be in a certain range which is from 0 to 1. That is basically the summary of Chapter 5. |
| Ch6 | Outlier detection was the main topic for Chapter 6. Based on this chapter, an Outlier is a data point that is far away from the majority of the correlated data. It is simply the values or certain data that are distanced or standing out from the mass. Additionally, there are methods in identifying Outliers, the first one is the Z-score method. This method, from its name alone, uses the formula of Z-score (Z = (X – μ) / σ.) to identify the Outlier. There is also the Inquartile Range or IQR Method that uses a certain formula along with its Lower bound and Upper bound. These concepts are simply the only ones that made a massive impact in the students' overall learnings in Chapter 6. |
| Ch7 | In Chapter 7, Feature selection was the main target. This chapter allowed the students to explore different methods on how to Filter data and features to establish a much more reliable result. Features can be processed simply by methods such as Recursive Feature Elimination or RFE that allows the user to scan the data for the best possible result. Additionally, having multiple methods to process certain features can be a handful sometimes. That is why the students had a specific method that they focused on to manage certain features, that method is the Wrapper method. This method simply ranks the features in a certain order that is based on their importance or relevance to the result. |
| Ch8 | Chapter 8 focuses on the Pipeline of data processing. The students were quite intrigued with the example given for this specific topic. It was simply a conveyor system that describes and explains the steps of the topic quite effectively, from processing raw data to having processed information due to stationary stops was quite helpful for discussing Pipeline. This chapter was heavy on the programming part and unlike the previous chapters, this chapter included topics (scaling and imputation) and concepts from the first few discussions. |
| Ch9 | The last chapter which is Chapter 9 focuses on Full Pipeline and Visualization or Plotting. Since the pipeline processing was discussed in Chapter 8, it makes sense to talk about the learnings from Visualization. This topic is simply about utilizing the Count plot of specified features in order to view such data in a graphical form. It is undeniable that having visual aids in analyzing and correlating data makes everything much easier and understandable. Among all the chapters, this chapter was quite the longest while also being the most interesting due to the different versions of graphical representations. |

## 🔍Errors we found

List any mistake you found in the original notebooks, and the correct version.
There are real ones in there. Finding them earns points.

| Chapter | Errors Found |
|---|---|
| Ch1_2_3 | No Errors Found  |
| Ch4 | No Errors Found |
| Ch5 | No Errors Found  |
| Ch6 | Possibly the Z-Score Filter value of 3 is erroneous. When filtering using 3, 100 does not get identified as an outlier; but changing the filter value to 2 does. |
| Ch7 | The syntax and instructions was right, however the value of Cross-Validation (CV) in the RFE program was wrong. Having 5 as the value of CV was an error, since there are required pairings in order to satisfy R2 (Coefficient of Determination). Assuming the data set given has 6 rows, having 5 as the value makes the number of pairs imbalanced or the array pairing is wrong. With 3, there are exact number of pairs that allows R2 to perform its equation and provide a result. |
| Ch8 | No Errors Found |
| Ch9 | No Errors Found |

## 🤖 Note on AI tools

The students used AI tools such as Gemini and Claude. Gemini was used for concept and idea verification, to ensure that there are no misconceptions between the actual idea of the topics and the students' learnings. As for Claude, it was used for program verification and descriptions, that allowed the students to answer the problem with Chapter 7's RFE program and other programming errors. 

## ⛓️References

McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly.
VanderPlas, J. Python Data Science Handbook.
Any other page or article you used.

---

*Prepared by Engr. Mikko De Torres, Department of Electronics Engineering*


# Chapter Questions:

## Chapter 1, 2, 3: Exploring and cleaning data

1. What is data preprocessing, and why do we do it before machine learning?
   
	ALDEN: TData pre-processing is a method or process to clean data by removing extraneous variables or fixing gaps in said data. Usually, it is done to observe data more clearly and see any existing patterns or trends.

	LODIAN: Data preprocessing is a method of utilizing and managing raw data to produce relevant and valuable information. Essentially, it is done by conducting a series of steps or specific procedures to break down, clean, and properly manage raw data.

2. What does each of these show you: head(), info(), and describe()?

	ALDEN: The Head() function displays if the data is numerical (int64 or float) or categorical (object). The info() function displays a sneak peek of the data by showing 5 (or more) rows from all columns. Lastly, describe() shows the statistical analysis summary (mean, median, mode, standard deviation, etc.) of the data.

    LODIAN: Each instruction or code allows me to see different aspects of the given data. For head(), it allows me to view the Rank, Title or Name of the game, as well as the Publishers of the game. As for the info(), it shows me the statistical data of the csv file, and for the describe() it allows me to see the different columns and titles presented in the head() earlier.
   
3. Which columns in the dataset had missing values? How many were missing in each?

	ALDEN: The Year and the Publisher columns of the dataset have values that are null. For the Year, it has 271 null values; while the Publisher column has 58 null values.

  	LODIAN: In the dataset, the columns with the missing values are the 'Year' and the 'Publisher'. For the column 'Year' it was missing 121 values or data, as for 'Publisher' it was missing 58.

6. The notebook showed two ways to handle missing data. Name both, and say when you would use each.

	ALDEN: There are 2 ways to handle missing data values, either deletion or imputation. Deletion can only be used if the amount of null values are very low but risks removing valuable information. Imputation, on the other hand, inputs calculated values into the missing values. Deletion can be done if the dataset is large, while imputation can be done if the dataset is small and deletion would shrink the dataset.

	> Claude AI has been used to understand the difference of the two. The answer is based on the student's understanding from the Notebook and the AI's explanation.

	LODIAN: The notebook named three strategies, namely Imputation, Deletion, and Prediction. For this specific dataset, I would use Imputation and Deletion only. Imputation is replacing data with computed values using numeric (mean) and categorical (mode) columns. As for Deletion, it simply removes columns and rows with missing values.

8. Why was the Rank column dropped from the dataset?

	ALDEN: From what I understand, the rank column just shows where a game - publisher places on a global scale based on sales. For me, this column does not pose any value in terms of information/data and can be removed from the dataset.

	LODIAN: In the file given, it was mentioned that due to irrelevance, Rank was removed from the dataset. It does not contribute much for the overall analysis and prediction and may also produce noise if not removed.

## Chapter 4: Feature engineering and encoding

1. What is feature engineering, in your own words?

	ALDEN: Feature engineering is a method of showing relationships between different sets of data. Like the example given in the colab, it shows a relationship or influence between temperature and sales. 

2. How was Lemonade per Degree computed, and what does it tell you about the sales?

	ALDEN: The lemonade per degree feature is calculated by dividing the amount of sales by the temperature value in Fahrenheit. The sales are showing to have a slightly positive relationship where the increase in temperature shows an increase in lemonade sales.

3. What is binning? List the four temperature labels used in the notebook.

	ALDEN: Binning is turning numerical data into categorical data. According to what is in the notebook; 71 – 75 is considered Cool, 76 – 85 is Warm, 86 - 95 is Hot, and 95 – 100 is Very Hot.

4. What is an interaction feature? Give the example from the notebook.

	ALDEN: An interaction feature is utilizing a variable with a new variable to produce a new feature. In the notebook, Ice cubes per Degree is used to show a relationship between the amount of ice used in the lemonade and the ambient temperature.

	>Claude AI has been used in this section for elaboration and understanding. The contents of the answer is based on the learner’s best understanding of the AI’s explanation. 

5. What is the difference between one-hot encoding and ordinal encoding?

	ALDEN: One-hot encoding gives an impression that only one quality will be present at a time. Ordinal encoding gives an impression of order or sequence that gradually changes (increases or decreases).

6. Why does ordinal encoding fit Little, Medium, Lots, while Sunny, Cloudy, Rainy needs one-hot?

	ALDEN: Ordinal encoding fits the little, medium, lots of categorical data because these categories gradually increasing values; it has a sequence where the smallest value can be assigned on 1 and the highest can be assigned on 3. Whereas, Sunny, Cloudy, and Rainy cannot be compressed into amounts and usually only one of these categories is happening at a time.

## Chapter 5: Scaling and normalization

1. What is data scaling, and what problem does it solve?

	ALDEN: Data scaling is a method of transforming multiple types of data into one in a comparable form. Usually, different data have wildly different values and scales and it would often be difficult to compare to one another due to said scales.
  
2. What does StandardScaler do to the mean and the standard deviation of a column?

	ALDEN: Based on additional resources, the StandardScaler apparently uses the mean/average and turns it into 0 while the standard deviation is used/turned into 1. It does not change the shape of the distribution, it just rescales it.
  
	>Claude AI has been used in this section for elaboration and deeper understanding of the question and its answer, the written output is the learning of the student. 

3. What range of values does MinMaxScaler give you?

	ALDEN: The range of values the MinMaxScaler ranges from the lowest value of the data column and assigns that to 0 and the highest value into 1. These extremes are then used as scales to map out the values in between the highest and lowest values. 
  
4. In the student example, which column had the bigger numbers? Why does that matter to a model?

	ALDEN: Under the student example, the grades column has the bigger numbers. It matters because that is the standard range of grades; any lower, and it risks implying that the student is not good at school.
  
5. Is scaling always needed? What does the answer depend on?

	ALDEN: It depends but usually yes. It depends on the difference of size and scale of the 2 columns because usually, the data is not directly comparable to each other.
  
## Chapter 6: Outlier detection

1. What is an outlier?

	ALDEN: An outlier is a data point that deviates from the standard/theoretical spread of data. It could be an extremely high or extremely low value that is positioned away from the majority of the data.

	

3. How does the Z-score method find outliers? What cutoff did the notebook use?

	ALDEN: The Z-score method filters values using the values obtained/mapped from the z-table and the standard deviation. The notebook uses a filter of 3; however due to 100 being 2.6, it is not filtered. Changing the filter value to 2 and 100 finally gets filtered.

	LODIAN:
  
5. How does the IQR method find outliers? Write the formula for the lower and upper fence.

	ALDEN: Outliers are identified in the IQR method if they are less than the lower fence or higher than the upper fence. The formula for the upper fence is [Q3 + (1.5 X IQR)] and the lower fence is [Q3 – (1.5 X IQR)]. The formula of the IQR is Q3 – Q1.
  
6. In the sample data, which value stands out from the rest? What is its Z-score?

	ALDEN: From the sample data given, 100 is very visually distinct from 10 or 22. Utilizing the Z-Score filtering method, I have observed that the Z-score is around 2.615.
  
7. Once you find an outlier, give two things you can do about it.

	ALDEN: Once an outlier has been identified, you can either delete the outlier or log transformation. Deleting the outlier can only be done if it is an error or could induce a bias; log transformation compresses the data and reduces the impact of the outlier.

## Chapter 7: Feature selection

1. What is feature selection, and why is it useful?

	ALDEN: Based on research, feature selection is a method that selects relevant features for prediction. It helps reduce inaccuracies in data. 
  
2. What does the filter method use to decide which features to keep?

	ALDEN: The filter method uses correlation in order to decide. Any data that does not have any form of correlation to the reference data will be dropped since there would be no observed relationship between the two and would likely be just random noise. 

	>Claude AI has been used in this section for elaboration and understanding. The contents of the answer is based on the learner’s best understanding of the AI’s explanation. 

3. What does RFECV do, step by step?

	ALDEN: RFECV first chooses an estimator model that determines the feature importance. Next, create the RFE object and compute the cross-validated score. Then fit the data and finally print. 

	>Claude AI has been used in this section for elaboration and understanding. The contents of the answer is also based on the Notebook and the learner’s best understanding of the AI’s explanation. 

4. What does LassoCV do to features that are not important?

	ALDEN: Essentially, LassoCV reduces the value of the useless feature until it reaches zero and lets it stay there; basically excluding them from the model.
  
	>Claude AI has been used in this section for elaboration and understanding. The contents of the answer is based on the learner’s best understanding of the AI’s explanation. 

5. Which features did each of the three methods choose? Put them in a short table.

| Methods | Features |
|---|---|
|Filter Method|relevant_features = correlations[correlations > 0.5]|
|Wrapper Method| estimator = SVR(kernel="linear")|
|Embedded Method|X = df_2.drop('final grade', axis=1)|


## Chapter 8: Constructing a preprocessing pipeline

1. What is a preprocessing pipeline? Explain it using the conveyor belt idea from the notebook.

	ALDEN: A preprocessing pipeline is a set of sequential steps of cleaning up data for use. Each step of cleaning data is like a station in a conveyor belt that does one specific thing.
  
2. The notebook gives three reasons for using a pipeline. Name all three.

	ALDEN: Automation for automatic preprocessing. Efficiency to streamline and reduce workflow time. Reliability/Reproducibility to maintain consistent results without human error.

3. What two steps were inside the pipeline, and in what order did they run?

	ALDEN: Within the preprocessing pipeline, the 2 steps inside it are: imputation, and scaling. Imputation to insert average value in the missing values of each column. While scaling standardizes the scale of the values.
  
  >Claude AI has been used in this section for identification of the steps and understanding their uses. The contents of the answer is based on the learner’s best understanding of the AI’s explanation.

4. What does ColumnTransformer do?

	ALDEN: The ColumnTransformer basically allows the user to simultaneously preprocess 2 different columns using 2 different methods. The results of this preprocessing will then produce a single unified output.

  >Claude AI has been used in this section to understand the uses. The contents of the answer is based on the learner’s best understanding of the AI’s explanation.

5. Which two columns of the Titanic dataset were preprocessed in this chapter?

	ALDEN: The preprocessed columns were the Age and Fare columns. 


## Chapter 9: Full pipeline and visualization

1. Which columns were handled as numerical, and which as categorical?

	ALDEN: For categorical data: PClass, Sex, and Embarked. While numerical data included: Age, and Fare.
  
2. How were the missing values filled in each of those two groups?

	ALDEN: Null values in the Fare  and Age were imputed with the median values of each of their respective columns. While null values in the categorical data were imputed with the word “Missing”.
  
3. What is discretization? What three age labels did the notebook use, and what age ranges do they cover?

	ALDEN: Discretization basically turns continuous data into distinct categories. The notebook use 0 – 12 to describe a “Child:, 12 – 50 to describe an “Adult”, 50 – 200 to describe the “Elderly”.
  
4. Name three of the plots you produced, and say in one sentence what each one shows.

  ALDEN: Bar Graph/Count Plot – A count plot is a visual representation of the amount of subjects within a specific category.

  Box Plot – It is a visual representation that shows the quartiles, minimum and maximum values, median, and outliers.

  Correlation Heatmap – This heat map shows the relationship/correlation between 2 different variables from -1 to 1, where -1 is perfect negative correlation and 1 perfect positive correlation.

5. Why is it useful to make plots after preprocessing instead of before?

  ALDEN: Preprocessing cleans up messy, unformatted, unscaled data in order to produce clean, scaled, and usable data that can be translated well into graphical plots. Preprocessing removes errors and noise from the data in order for the plots to be actually intelligible for the one accessing the information.


