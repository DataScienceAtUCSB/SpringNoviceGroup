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
2. Click around the sites linked below to find a cool dataset. When your team decides on one, download a `.csv` file and head to the next section
    * [r/datasets](https://www.reddit.com/r/datasets/) is a subreddit full of datasets. Try sorting by popularity.
    * [kaggle.com](https://www.kaggle.com/datasets) has a lot of cool data
    * [AWS](https://aws.amazon.com/public-datasets/) hosts a lot of datasets in publicly accessible S3 Buckets. Accessing this data will be a little trickier than just downloading a `.csv`, but you will win serious brownie points!
    * [National Bureau of Economic Research](http://www.nber.org/data/) puts up a lot of free datam go crazy!
3. Make sure you get a mix of continuous and categorical variables!
4. Set up a git repo for your team's project
    * This will hold your data and R scripts

### Cleaning Data

1. You can read basic files (`.csv`, `.txt`) using R's `read.csv()` and `read.table()` functions. Look at your data in a text editor and figure out what type of *delimiter* your dataset uses
    * Common delimiters are commas and tabs
2. Once loaded into R, calculate some summary statistics and dimensions of the data
    * For each continuous column, get the Interquartile Range
    * For each categorical column, make a frequency table
3. I am willing to bet that your data has some errors. Perhaps a value was incorrecty entered by the creator, or R misinterpreted a data type. Welcome to the real world! Gone are the days of perfectly clean datasets
4. Get good at Googling your problem. Every problem your team has from this point forward *has been encountered, asked, and answered* before.
    * Is your column a string type and needs to be numeric? Use `as.numeric()`
    * 

