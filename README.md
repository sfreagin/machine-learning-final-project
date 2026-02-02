<!-- hide -->
# Machine Learning final project
<!-- endhide -->

- Throughout this bootcamp, we have studied different models based on projects of different areas and types. Now it's time to create your own project using the algorithm that you think is best suited to your problem.
- You will have to find a suitable dataset to work with, process it, train a model and finally make it available for consumption.

> “Hard work always beats talent when talent doesn't work hard” - Tim Notke
  
## 🌱  How to start this project

1. Create a new repository based on [machine learning project](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) by [clicking here](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Open the newly created repository in Codespace using the [Codespace button extension](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).
3. Once the Codespace VSCode has finished opening, start your project by following the instructions below.
4. Start your project by following the instructions below.

## 🚛 How to deliver this project

Once you have finished the project, you must deliver:

- The link to your Github repository (already implemented).
- The link to your implemented Machine Learning web application.

## 📝 Instructions

### Group formation

To carry out the final project, students will be organized in teams of 2 to 3 people. The work must be collaborative.

### Project phases

#### Step 1: Problem definition

Start by defining a problem and turn it into a Machine Learning problem. This is the first step, since the data must meet a certain need and the Machine Learning process must aim at satisfying that need.

The choice of the data set must satisfy minimum requirements in terms of number of rows and predictor variables. At a minimum, it must contain:

- 60,000 instances (rows)
- 20 predictor variables, of which there must be at least 1 categorical variable.

> NOTE: Depending on the dataset and the case study to be explored, datasets that do not reach the established minimum may be evaluated and accepted.

#### Step 2: Acquiring and loading the data set

Since in the real world data does not usually arrive in a flat csv file, this data must be acquired by one of the following ways:

- Extracting data from some web page or portal using web scraping techniques.
- Exploitation of a public database using SQL language (the database must support this language).
- Exploitation of a public API to obtain data.

Once you have the data, you must store it in a CSV document and load it into Python using Pandas.

> NOTE: Depending on the dataset and the case study to be explored, datasets downloaded by other means could be evaluated and accepted.

#### Step 3: Store the information

A widely used practice is to store the data, especially if they are massive, in a database for quick access to them. From all the databases we have studied, choose the one most compatible with your data and store it there. Then, perform queries using Python (with pure SQL code or using the wrappers we have studied in the course) to use the different statements: `SELECT`, `JOIN`, `INSERT`.... These queries must provide a value to start the analysis on the data prior to the statistics and EDA.

It is important to understand that in the real world we do not only have CSV as an ally to store data, since it is easier to lose a flat file like CSV than a database with its connections and data models inside. Security is also a critical and important factor for storing your data there, since a CSV does not provide any protection mechanism that other technologies do.

#### Step 4: Perform a descriptive analysis

The raw data stored in a database can be a great and very valuable source of information. Before we begin to simplify and exploit them with EDA, we must know their fundamental statistical measures: means, modes, distributions, deviations, etcetera. Analyze the descriptive statistical variables of each of the predictors of the data set and theorize about the distribution that each of them follows.

Use hypothesis tests if you consider it necessary.

#### Step 5: Perform a full EDA

This step is vital to ensure that we keep the variables that are strictly necessary and eliminate those that are not relevant or do not provide information. Use the example Notebook we worked on and adapt it to this use case.

Make sure to conveniently divide the data set into `train` and `test` as we have seen in previous lessons.

#### Step 6: Build the model and optimize it

Once you have your data ready, decide which model fits best and train it. If in doubt, try using several of the ones you have already studied. Select the one that best fits the data.

Remember that the hyperparameter optimization step is very important to explore and achieve the best version of the model.

#### Step 7: Deploy the model

Create a Machine Learning web application using your saved model. You can use Flask, Streamlit or any other tool you know.
Use Heroku, Render or another cloud computing platform of your choice to deploy your web application and share it with the world. Remember that the application is going to be the gateway to potential users or customers, and you have to take care of even the smallest detail.

### Presentation

The presentation will last 5 minutes per group, so be sure to use your time efficiently. The code will be reviewed, so don't waste time explaining it. Focus on the important points, as if you were trying to sell the project to your company's stakeholders or investors. Keep in mind that they probably don't have a technical background, so try to use simple words and an easy-to-understand presentation. Remember that quality trumps quantity.

Recommended important points to mention in your 5-minute presentation:

- What is the business problem you want to solve?
- How did you collect the data?
- Important patterns found in the data
- What algorithm and evaluation metrics did you use to build your final model?
- Show your web application at work and mention how it can be improved in the future.

> “The secret to getting ahead is to start.” - Mark Twain
