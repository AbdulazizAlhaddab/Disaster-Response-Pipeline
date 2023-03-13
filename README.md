# Disaster Response Pipeline Project

### Description:

The initial dataset includes pre-labeled tweets and communications from real-world tragedies. This project's goal is to create a Natural Language Processing tool that categorizes texts.

The Project is divided into the following Sections:

1. Data Processing, ETL Pipeline to extract data from source, clean data and save them in a proper databse structure.
2. Machine Learning Pipeline to train a model which is able to classify text messages in 36 categories.
3. Web Application using Flask to show model results and predictions in real time.

### Data:

Figure Eight - Multilingual Disaster Response Messages provided the data for this project. This dataset contains 30,000 messages derived from events such as an earthquake in Haiti in 2010, an earthquake in Chile in 2010, floods in Pakistan in 2010, superstorm Sandy in the United States of America in 2012, and news items spanning several years and hundreds of disasters.

Data includes 2 csv files:

1. disaster_messages.csv: Messages data.
2. disaster_categories.csv: Disaster categories of messages.

### Installation:

This project requires Python 3.x and the following Python libraries:

* Machine Learning Libraries: NumPy, SciPy, Pandas, Sciki-Learn
* Natural Language Process Libraries: NLTK
* SQLlite Database Libraqries: SQLalchemy
* Web App and Data Visualization: Flask, Plotly

### Instructions:

1. Clone this repository

```
git clone git@github.com:prateeksawhney97/Disaster-Response-Pipeline.git
```

2. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/Disaster_Response.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/Disaster_Response.db models/classifier.pkl`

3. Run the following command in the app's directory to run your web app.
    `python run.py`

4. Go to http://0.0.0.0:3001/

### Screenshots:

#### 1. Home Page

![image](https://user-images.githubusercontent.com/121203927/224565306-c209e3fa-8b7e-4e37-ad27-b94a7ece7412.png)
![image](https://user-images.githubusercontent.com/121203927/224565366-dbd02447-88ff-40c3-95d4-62dcd8877dad.png)
![image](https://user-images.githubusercontent.com/121203927/224565348-7b944afa-c83c-4427-bad1-eccb48d5f0ae.png)

#### 2. Classify Messages Page

INPUT- Its raining heavily since yesterday here 

![image](https://user-images.githubusercontent.com/121203927/224565627-4a3b07d0-dc0b-472c-9004-9f4dff6c3a9b.png)

PREDICTED CLASSES- 

![image](https://user-images.githubusercontent.com/121203927/224565642-05be54e1-f55a-46bb-8ab5-ad2e9a53eac9.png)

INPUT- Please provide healthcare equipments and medicines

![image](https://user-images.githubusercontent.com/121203927/224565552-55fecf97-e3c6-4c19-8361-680f5fca7cf3.png)

PREDICTED CLASSES- 

![image](https://user-images.githubusercontent.com/121203927/224565574-efafe400-57ff-4b8e-a287-70c5429ca06d.png)
![image](https://user-images.githubusercontent.com/121203927/224565594-54859a7e-decd-4f1f-a3d4-fba595ec7984.png)

INPUT- Please help us with food and water 

![image](https://user-images.githubusercontent.com/121203927/224565760-0373a44d-49d6-4f45-b042-1f331cda8dff.png)


PREDICTED CLASSES- 

![image](https://user-images.githubusercontent.com/121203927/224565775-cfc85dcb-c2eb-4e67-8578-3b058af9d694.png)

![image](https://user-images.githubusercontent.com/121203927/224565783-beb05b69-758c-48b9-9044-5452b410b466.png)
