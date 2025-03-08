# F1-Prediction-Project
Class - CS105

In this project, we will be trying to predict the standings of the Formula 1(F1) Driver's Championship.

We will use a dataset found on GitHub that was made by user "toUpperCase78", which can also be found at this link: https://github.com/toUpperCase78/formula1-datasets/tree/master

From this dataset, we want to use the driver's team, their number of podium finishes, their fastest laps for races, their finishing and starting positions, and their podium percentage to determine their final Driver's Championship.

Our procedure is as follows:

    Data cleaning and pre-processing:
        Removing un-needed values
        Removing missing data
        Adding any valuable non-included data (actual driver's standings for the championship)
        Saving the data in a desirable form (Data Wrangling and Data Munging)

    EDA:
        Explore our data with graphs, correlations, and normality tests
        Find correlations between our variables and analyze them
        Find the results of our hypotheses

    ‘Main Part’:
        We want to use K-means clustering for our unsupervised learning technique
            We will try to group drivers based on variables like lap times, pole positions, and podium percentages
            From these groups, we will try and see if they provide insight into helping us predict the Driver’s Championship standings 
        For our supervised learning, we will use Gradient Descent to try and predict the standings
            Using the variables mentioned above, including the clusters from the K-means clustering, we want to make a model that can predict the driver’s standings.
        KNN
            We will use KNN to also predict the Driver's standings.

    Analysis and making the project


