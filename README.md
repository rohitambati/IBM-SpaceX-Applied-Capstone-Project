## Project Overview:

SpaceX has gained worldwide attention for a series of historic milestones. It is the only private company ever to return a spacecraft from low-earth orbit, which it first accomplished in December 2010. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars wheras other providers cost upward of 165 million dollars each, much of the savings is because Space X can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch.

In this capstone project, we will predict if the Falcon 9 first stage will land successfully. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch. This dataset includes a record for each payload carried during a SpaceX mission into outer space.

## Steps:

1. Web scrap Falcon 9 launch records with BeautifulSoup:
    - Extract a Falcon 9 launch records HTML table from Wikipedia.
    - Parse the table and convert it into a Pandas data frame.
2. Request to the SpaceX API, perform data wrangling and formating.
3. Clean the requested data.
4. Perform Exploratory Data Analysis and determine Training Labels.
5. Perform Exploratory Data Analysis and Feature Engineering using Pandas and Matplotlib.
6. Perform Exploratory Data Analysis using SQL, DB2.
7. Launch Sites Locations Analysis with Folium.
8. Create machine learning pipeline to predict if the first stage will land from data acquired at previous stages.
9. Perform exploratory Data Analysis and determine Training Labels:
    - Standardize the data.
    - Split into training data and test data.
    - Find best Hyperparameter for SVM, Classification Trees and Logistic Regression.
    - Find the method performs best using test data.

Badge: [IBM Data Dcience Professional Certificate](https://www.credly.com/badges/ec3aa0b1-634f-466e-a57c-188e25eac345)
