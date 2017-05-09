## Data Visualization

### About the Project
_If a picture is worth a thousand words, then a data visualization is worth a million._ A good data visualization should make it easy for the viewer to digest otherwise complex trends. There are a lot of schools of thought when it comes to visualizing data, but you have to learn before you can walk! In this project, you will get acquainted with the ggplot2 and Shiny libraries in R.

Like the other two projects, this outline is designed to guide you through making a data visualization. This sheet not _instruct_ you on each step, persay. You may be given an instruction partway through to "use ggplot to make a layered density plot with each of the three categories". If that doesn't make immediate sense by the time you read that step, head to Google or ask for clarification.

Once you get comfortable with ggplot2, I highly recommend taking this project in a direction that interests your group. If you visualize an interesting trend, maybe you could fit a regression model to better quantify the trend.

### Technical Details

I wrote this project assuming that your group will be using R, not Python. Python _does_ have a plotting library, matplotlib, but we will eventually make these visualizations interactive using R's Shiny library. So make sure each member on your team has R and RStudio installed.

### Steps to Success

#### Finding Data

1. So you want to make a data visualization? You are going to need some data! Pick something that is interesting to you and your team. *And make sure* you have enough variables (columns) to make the visualization worthwhile
    * Try to find a dataset with a mix of categorical and continuous variables
2. Click around the sites linked below to find a cool dataset. When your team decides on one, download a `.csv` file and head to the next section. Make sure you and your team decide on a question to ask about your chosen dataset. **Then write it down**, this will be the question your visualizations will attempt to answer or investigate. You *need* to have a guiding question--otherwise you will never know when you are officially done with the project.
    * [r/datasets](https://www.reddit.com/r/datasets/) is a subreddit full of datasets. Try sorting by popularity.
    * [kaggle.com](https://www.kaggle.com/datasets) has a lot of cool data
    * [AWS](https://aws.amazon.com/public-datasets/) hosts a lot of datasets in publicly accessible S3 Buckets. Accessing this data will be a little trickier than just downloading a `.csv`, but you will win serious brownie points!
    * [National Bureau of Economic Research](http://www.nber.org/data/) puts up a lot of free datam go crazy!
3. Make sure you get a mix of continuous and categorical variables!
4. Set up a git repo for your team's project
    * This will hold your data and R scripts
5. Get good at Googling your problem. From this point forward, every problem your team comes across *has already been encountered, asked, and answered* before.
    * Is your column a string type and needs to be numeric? Google "R how to convert a column to numeric"
    * Need to make a smaller sample of the data? Google "R subset data write to file"
    
### Summarising Data

1. You can read basic files (`.csv`, `.txt`) using R's `read.csv()` and `read.table()` functions. Look at your data in a text editor and figure out what type of *delimiter* your dataset uses
    * Common delimiters are commas and tabs
1. If your dataset is very large, try downsampling the data and writing that subset to a seperate file.
    * Then you can use that for testing. When everything works you cna rerun everything with the full script
2. Once loaded into R, calculate some summary statistics and dimensions of the data
    * For each continuous column, get the Interquartile Range
    * For each categorical column, make a frequency table
3. I am willing to bet that your data has some errors. Perhaps a value was incorrecty entered by the creator, or R misinterpreted a data type. Welcome to the real world! Gone are the days of perfectly clean datasets, let's cover some basic data cleaning.

### Cleaning Data
1. Check for missing values in your dataset. Count them by each column. Is there any systemic pattern to the missing values? 
    * They may be coded as 0, NA, NULL, or some arbitrary string entered by the creator of the dataset
2. Decide how to handle the missing values. A common solution is just to remove rows with missing values. But what if that means you need to remove 50% of your observations? Take a moment to discuss options with your team.
    * Impute the missing data?
    * Remove the observations?
    * If the missingness is systematic, perhaps you could use that information to better impute/
3. Next, we need to handle outlier values. In step 3 of **Summarising Data**, you made tables for each column to investigate their ranges. Undoubtedly, some values are going to be encoded *incorrectly* in your dataset. Common examples are negative values for patients' ages, Longitute/Latitude coordinates that point to the wrong city, having a value of 6 when the scale only ranges from 1 to 5. Find those outliers and decide what to do with them.
    * Remove them? Impute with the mean? How will your decision affect the data visualization?
4. You may find that you have odd characters hanging around where they shouldn't. In a vector of numeric values you might have <code>c(1, 2e, 3, 4e, 5, 6e, ...)</code>. For some reason, the even numbers have the 'e' character following them. If you run into  similar situation, check out [Regular Expressions](https://www.r-bloggers.com/regular-expressions-in-r-vs-rstudio/).
    * Regular expressions define a syntax to search strings and either return or replace the matching substrings

### ggplot2

1. Don't use the base R graphics package.
2. Head to DataCamp and complete [this course](https://www.datacamp.com/courses/data-visualization-with-ggplot2-1) and [this course](https://www.datacamp.com/courses/data-visualization-with-ggplot2-2/?utm_campaign=data-visualizaiton-with-ggplot2-2&utm_medium=datacamp-community&utm_source=standard_marketing_schedule) with your team. It will introduce you to the ggplot2 R package. 
3. Once you complete those courses, make some of your own basic visuals like bar plots, histograms, and scatterplots.
    * These plots don't have to be the ones answering your original question from **Finding a Dataset**, step 2. Just start easy!
4. Then try incorporating size, color, and transparency to show the user more information.
5. Don't forget your axis labels, titles, legends, and legend titles. You can even include a caption on the bottom to better help the viewer injest the visualization.
6. Show your visualizations to Jason or Ravi for feedback.
    * Use the feedback to improve the plots!
7. Now sketch out some plots on paper to try to answer/investiage your team's guiding question.
    
    
    
