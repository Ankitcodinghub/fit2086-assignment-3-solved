# fit2086-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [FIT2086 Assignment 3 Solved](https://www.ankitcodinghub.com/product/fit2086-assignment-3-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119386&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;FIT2086 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Introduction

Submission: No files are to be submitted via e-mail. Correct files are to be submitted to Moodle, as given above. You must submit the following three files:

1. One PDF file containing a report with all non-code answers to all the questions that require written answers. This file should also include all your plots.

2. One R script files containing R code to answer Questions 1, 2 and 3, as required.

Please read these submission instructions carefully and take care to submit the correct files in the correct places.

2. How would your assessment of which predictors are associated change if you used the Bonferroni procedure with α = 0.05? [1 mark]

4. Use the stepwise selection procedure, with the BIC criterion (use direction=”both”), to prune out potentially unimportant variables. Write down the final regression equation obtained after pruning. [1 mark]

6. Table 2 gives the values of predictors for a new suburb. Use the model found in Question 1.4 to predict the median house price for this suburb. Provide a 95% confidence interval for this prediction. [1 mark]

7. A friend who works at a local council suggests that they believe there is possibly an interaction effect between the number of rooms a dwelling has and its distance to one of the employment centres. Assess whether you think this is the case, and what effect it has on the model? [1 mark]

Variable name Description Values

crim Per-capita crime rate &gt; 0

zn Proportion of residential land zoned for lots over 25,000 sq. ft. 0 − 100

indus Proportion of non-retail business acres per town 0 − 100

chas Does the suburb front the Charles River? 0 = No, 1 = Yes

nox Nitric oxides concentration (parts per 10 million) 0

rm Average number of rooms per dwelling

age Proportion of owner-occupied units built prior to 1940

dis Weighted distances to five Boston employment centres

rad Index of accessibility to radial highways

tax Full-value property-tax rate per $10,000

ptratio Pupil-teacher ratio

lstat Percentage of “lower status” of the population

medv Median value of owner-occupied homes in $1,000s

Table 1: Boston Housing Data Dictionary.

Variable crim zn indus chas nox rm age dis rad tax ptratio lstat Value 0.04741 0 11.93 0 0.573 6.03 80.8 2.505 1 273 21 7.88

Table 2: Boston Housing Data Dictionary.

some text

• provide the R code you used to answer the questions in your R script. Please use comments to ensure that the code used to identify each question is clearly identifiable.

• Provide appropriate written answers to the questions, along with any graphs, in the report document.

When answering this question, you must use the rpart package that we used in Studio 9. The wrapper function for learning a tree using cross-validation that we used in Studio 9 is contained in the file wrappers.R. Don’t forget to source this file to get access to the function.

3. For classification problems, the rpart package only labels the leaves with the most likely class. However, if you examine the tree structure in its textural representation on the console, you can determine the probabilities of having heart disease (see Question 2.3 from Studio 9 as a guide) in each leaf (terminal node). Take a screen-capture of the plot of the tree (don’t forget to use the “zoom” button to get a larger image) or save it as an image using the “Export” button in R

Studio.

Then, use the information from the textual representation of the tree available at the console and annotate the tree in your favourite image editing software; next to all the leaves in the tree, add text giving the probability of contracting heart disease. Include this annotated image in your report file. [1 mark] 4. According to your tree, which predictor combination results in the highest probability of having heart-disease? [1 mark]

6. Write down the regression equation for the logistic regression model you found using step-wise selection. [1 mark]

8. Calculate the odds of having heart disease for the 69th patient in the test dataset. The odds should be calculated for both:

(a) the tree model found using cross-validation; and (b) the step-wise logistic regression model.

9. For the logistic regression model using the predictors selected by BIC in Question 2.6, use the bootstrap procedure (use at least 5,000 bootstrap replications) to find a confidence interval for the probability of having heart disease for the 69th patient in the test data. Use the bca option when computing this confidence interval. Discuss this confidence interval in comparison to the predicted probabilities of having heart disease for both the logistic regression model and the tree

Variable name Description Values

AGE Age of patient in years 29 − 77

SEX Sex of patient M = Male

F = Female

CP Chest pain type Typical = Typical angina

Atypical = Atypical angina

NonAnginal = Non anginal pain

Asymptomatic = Asymptomatic pain

TRESTBPS Resting blood pressure (in mmHg) 94 − 200

CHOL Serum cholesterol in mg/dl 126 − 564

FBS Fasting blood sugar &gt; 120mg/dl ? &lt;120 = No

&gt;120 = Yes

RESTECG Resting electrocardiographic results Normal = Normal

ST.T.Wave = ST wave abnormality

Hypertrophy = showing probable hypertrophy

THALACH Maximum heart rate achieved 71 − 202

EXANG Exercise induced angina? N = No

Y = Yes

OLDPEAK Exercise induced ST depression relative to rest 0 − 6.2

SLOPE Slope of the peak exercise ST segment Up = Up-sloping

Flat = Flat

Down = Down-sloping

CA Number of major vessels colored by flourosopy 0 − 3

THAL Thallium scanning results Normal = Normal

Fixed.Defect = Fixed fluid transfer defect

Reversible.Defect = Reversible fluid transfer defect

HD Presence of heart disease N = No

Y = Yes

Table 3: Heart Disease Data Dictionary. ST depression refers to a particular type of feature in an electrocardiograph (ECG) signal during periods of exercise. Thallium scanning refers to the use of radioactive Thallium to check the fluid transfer capability of the heart.

Figure 1: Noisy measurements from a (simulated) mass spectrometry reading. The “true” (unknown) measurements are shown in orange, and the noisy measurements are shown in blue.

Data Smoothing

Data “smoothing” is a very common problem in data science and statistics. We are often interested in examining the unknown relationship between a dependent variable (y) and an independent variable (x), under the assumption that the dependent variable has been imperfectly measured and has been contaminated by measurement noise. The model of reality that we use is

y = f(x) + ε

where f(x) is some unknown, “true”, potentially non-linear function of x, and ε ∼ N(0,σ2) is a random disturbance or error. This is called the problem of function estimation, and the process of estimating f(x) from the noisy measurements y is sometimes called “smoothing the data” (even if the resulting curve is not “smooth” in a traditional sense, it is less rough than the original data).

In this question you will use the k-nearest neighbours machine learning technique to smooth data. This technique is used frequently in practice (think for example the 14-day rolling averages used to estimate coronavirus infection numbers). This question will explore its effectiveness as a smoothing tool.

Mass Spectrometry Data Smoothing

the samples ms.measured$intensity and the value of the true spectrum ms.truth$intensity are plotted in Figure 1 against their respective MZ values. To answer this question you must:

• provide the R code you used to answer the questions in your R script. Please use comments to ensure that the code used to identify each question is clearly identifiable.

• Provide appropriate written answers to the questions, along with any graphs, in the report document.

Questions

1. For each value of k = 1,…,25, use k-NN to estimate the values of the spectrum at each of the MZ values in ms.truth$MZ. Then, compute the mean-squared error between your estimates of the spectrum, and the true values in ms.truth$intensity. Produce a plot of these errors against the various values of k. [1 mark]

5. Use the cross-validation functionality in the kknn package to select an estimate of the best value of k (make sure you still use the optimal kernel). What value of k does the method select? How does it compare to the (in practice, unknown) value of k that would minimise the actual mean-squared error (as computed in Question 3.1a)? [1 mark]

6. Using the estimate of the spectrum produced in Q3.5 using the value of k selected by crossvalidation, and the values in ms.measured$intensity, see if you can think of a way to find an estimate of the standard deviation of the sensor/measurement noise that has corrupted our intensity measurements. [1 mark]

7. An important task when processing mass spectrometry signals is to locate the peaks, as this gives information on which elements are present. From the smoothed signal produced using the value of k found in Question 3.5, which value of MZ corresponds to the maximum estimated abundance? [1 mark]
