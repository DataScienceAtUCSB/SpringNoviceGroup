
<h1>Data Science at UCSB</h1>
<h2>Beginner Project: Predicting Fatalities of the USS Titanic</h2>


<h3>About the Project</h3>
<p>
	In this project, you and your team will be working with a classic dataset known to Data Scientists and enthusiasts ubiquitously as "the Titanic dataset". The data has records of every registered passenger on the Titanic along some variables like sex, age, title, class, <em>and most importantly</em>... death! Your eventual end-goal will be to build an learning ensemble constisting of logsitic regression, k-Nearest Neighbors (kNN), and a classification tree. When your team is happy with the model's performance, you can submit your predictions to the Kaggle competition!
</p>
<p>
	This is what we would call a "supervised machine learning binary classification problem". It is "supervised" because we have a set of explanatory variables (age, sex, etc.) and a matching response variable (death). And it is a "binary classification problem" because our Y takes on two values: 0 or 1. This is unlike a regression problem where our response can take on values on the real number line. Our goal is to learn the mapping, F(), from our matrix of explanatory variables, X, to our response, Y.
</p>
<p>
	To be successful in this project, I suggest having at least one team member that has completed PSTAT 126. Preferably, you would also have a student that is taking PSTAT 131 this quarter as well. However, this is a classic dataset and a classic task for the data--so there are plenty of resources online. I attached a list of good resources at the bottom of this page.
</p>

<h3>Technical Details</h3>
<p>
	As mentioned earlier, your final goal is to build an <em>ensemble</em> of logistic regression, kNN, and a classification tree. An ensemble means that we will fit each of these three models to our training data, and they will all contribute to the final prediction. The most basic approach is to take a majority vote for each observation--if kNN and logistic regression predicted death for an observation, then we predict death. Alternatively, we could average the three predicted <em>probabilities</em>. You could get even more technical and use weighted averages if it seems that one model, say the classification tree, is performing very well.
</p>
<p>
	In the section below, I outline the general phases of the project. I did my best to include keywords and references, so research those on Google or the books at the bottom. Please do <strong>not</strong> treat it as a guidebook. One bullet point may take one line of code, and the next might take all meeting.
</p>

<h3>Steps to Success</h3>
<h4>Exploratory Analysis</h4>
<ol>
	<li>
		Download the dataset from Kaggle.com
		<ul>
			<li>
				If you are asked to download "train.csv" or "test.csv", only use the <strong>training</strong> set
			</li>
			<li>
				We will come back to "test.csv" at the very end when we submit to Kaggle
			</li>
		</ul>
	</li>
	<li>
		Start an R or Python script called explore.R or explore.py
	</li>
	<li>
		Make visualizations of each explanatory variable to the response
		<ul>
			<li>
				Using R? Use ggplot. Using Python? Use matplotlib.
			</li>
			<li>
				Take some time on this, you might find a trend to help in modeling
			</li>
		</ul>
	</li>
	<li>
		Create a correlation matrix of your explanatory variables
		<ul>
			<li>
				Bonus points: use ggplot to color-code each cell of the matrix
			</li>
			<li>
				Red = high correlation, blue = low correlation
			</li>
		</ul>
	</li>
	<li>
		What are the maximum and minimum values of the continuous predictors?
	</li>
	<li>
		How many unique values are in each categorical predictor?
		<ul>
			<li>
				<em>Would it be bad if a categorical predictor had a lot of unique values? Say 200 values? Why?</em>
			</li>
			<li>
				If it is bad, what could we do to fix it? Think simply.
			</li>
		</ul>
	</li>
</ol>

<h4>Cross Validation</h4>
<p>
	Before we begin modeling, it is crucial that everyone on your team understand the idea of cross validation. Before continuing to the next section on logistic regression, make sure everyone on your team can answer each of these questions. 
</p>

<ol>
	<li>
		What is a training set?
	</li>
	<li>
		What is a test set?
	</li>
	<li>
		Why should I <strong>not</strong> test my model on the training data?
	</li>
	<li>
		What is the Bias-Variance tradeoff?
		<ul>
			<li>
				------- put wikipedia link here ---------
			</li>
		</ul>
	</li>
	<li>
		Explain the process of k-Fold Cross Validation to your teammates. 
		<ul>
			<li>
				Use the whiteboard, draw pictures!
			</li>
		</ul>
	</li>
	<li>
		Why is raw accuracy <strong>not</strong> a good measure of classifier model performance?
		<ul>
			<li>
				What are two more common measures of model performance? 
			</li>
			<li>
				<em>Hint</em>: they sound really similar
			</li>
		</ul>
	</li>
</ol>

<h4>Logistic Regression</h4>
<p>
	Logistic regression is actually very similar to normal, linear regression. In linear regression our response is a Gaussian random variable, but in classification it is definitely not Gaussian--our only possible values are 0 or 1. So we follow the same procedure as linear regression (as far as finding the H matrix, getting coefficients). But at the very end we pass our fitted values (B + XB + ...) into the logit function. Now our output is a probability and we can apply a threshold for making classifications. A common threshold, of course, is 0.50.
</p>
<ol>
	<li>
		First try splitting the data into training and testing sets
		<ul>
			<li>
				No k-Fold Cross Validation, just 1 training set and 1 test set
			</li>
		</ul>
	</li>
	<li>
		Fit a logistic regression model to the training set
	</li>
	<li>
		Analyze the coefficients of the model
		<ul>
			<li>
				If you are in R, use <code>summary()</code> and analyze the significance levels
			</li>
		</ul>
	</li>
	<li>
		Make predictions on the test set using the explanatory variables
		<ul>
			<li>
				This will require you to subset dataframe before or as it is being passed to the prediction function
			</li>
		</ul>
	</li>
	<li>
		Calculate the sensitivity and specificity of the model's performance on the test set
	</li>
	<li>
		Print a confusion matrix
	</li>
</ol>

<h4>k Nearest Neighbors (kNN)</h4>
<p>
	kNN is a popular supervised Machine Learning algorithm. It is a <em>lazy</em> algorithm meaning that it does not build a "model" in the classical sense like linear or logistic regression. Instead, when we ask the algorithm to predict for a given observation, it will find the nearest <strong>k</strong> observations and predict using a majority vote of those nearest observations' classes. It is what we call a "lazy" algorithm. <strong>k</strong> is a hyper parameter and must be chosen by the modeler. <strong>k</strong> is often chosen through cross validation. That means we choose the value for <strong>k</strong> that maximized specificty, sensitivity, or both.
</p>

<ol>
	<li>
		Create partitions for k-Fold Cross Validation
	</li>
	<li>
		Decide on some values for k
	</li>
	<li>
		You will need to perform cross validation <strong>and</strong> test your chosen values for k
		<ul>
			<li>
				You can think of this as nested for-loops
			</li>
			<li>
				The top loop iterates over the folds, and the inner loop iterates over values for k
			</li>
			<li>
				So you can literally write two for loops with an accumulator for the model performances, or see if there is an appropriate package/class in R/Python
			</li>
		</ul>
	</li>
	<li>
		What value of <strong>k</strong> did best?
	</li>
	<li>
		Why <strong>can't</strong> we make a direct comparison to our logistic regression model's perfomance?
	</li>
</ol>

<h4>Classification Trees</h4>
<p> </p>
<ol>
	<li>
		Using the same number of folds that you used in the kNN modeling phase, 
	</li>
</ol>

<h4>Building the Ensemble</h4>
<p>
	
</p>
<ol>
	<li>
		
	</li>
</ol>

<h4>Submitting to Kaggle</h4>
<p>
	
</p>
<ol>
	<li>
		
	</li>
</ol>

<h4>Resources</h4>
<ul>
	<li>
		Predictive Modeling with Applications in R
	</li>
	<ul>
		<li>
			The club has a physical copy of this book
		</li>
		<li>
			Introduction to Statistical Learning is slightly better in explaning the algorithms themselves
		</li>
	</ul>
	<li>
		
	</li>
	<li>
		
	</li>
	<li>
		
	</li>
	<li>
		
	</li>
	<li>
		
	</li>
</ul>
