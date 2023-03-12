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

### Screenshots:

#### 1. Home Page

![Screenshot from 2020-05-12 22-57-43](https://user-images.githubusercontent.com/34116562/81772729-39c76c80-9504-11ea-85e9-e5f45db2cbf6.png)
![Screenshot from 2020-05-12 22-57-48](https://user-images.githubusercontent.com/34116562/81772741-3d5af380-9504-11ea-9ce3-afc7e78dddda.png)
![Screenshot from 2020-05-12 22-57-53](https://user-images.githubusercontent.com/34116562/81772747-41871100-9504-11ea-942b-38846c7d49bf.png)
![Screenshot from 2020-05-12 22-58-21](https://user-images.githubusercontent.com/34116562/81772751-451a9800-9504-11ea-9fe6-76bae5341ad4.png)

#### 2. Classify Messages Page

INPUT- Please provide healthcare equipments and medicines (EXAMPLE-1)

![Screenshot from 2020-05-12 22-58-46](https://user-images.githubusercontent.com/34116562/81772761-4c41a600-9504-11ea-88af-90ecd9eb4ff5.png)

PREDICTED CLASSES- 

![Screenshot from 2020-05-12 22-58-56](https://user-images.githubusercontent.com/34116562/81772878-9b87d680-9504-11ea-8190-b9e4c8ae9e5b.png)
![Screenshot from 2020-05-12 22-58-59](https://user-images.githubusercontent.com/34116562/81772887-9fb3f400-9504-11ea-8ed5-aae7f9d51e2d.png)

INPUT- Its raining heavily since yesterday here (EXAMPLE-2)

![Screenshot from 2020-05-12 22-59-10](https://user-images.githubusercontent.com/34116562/81773045-13560100-9505-11ea-8a95-f0992ec2236e.png)

PREDICTED CLASSES- 

![Screenshot from 2020-05-12 22-59-18](https://user-images.githubusercontent.com/34116562/81773048-14872e00-9505-11ea-874f-b5fa49ac5d28.png)


INPUT- Please help us with food and water (EXAMPLE-3)

![Screenshot from 2020-05-12 23-00-55](https://user-images.githubusercontent.com/34116562/81773447-e3f3c400-9505-11ea-966a-e83099565f2a.png)


PREDICTED CLASSES- 

![Screenshot from 2020-05-12 23-00-59](https://user-images.githubusercontent.com/34116562/81773451-e6eeb480-9505-11ea-93c3-f44885c83960.png)

![Screenshot from 2020-05-12 23-01-03](https://user-images.githubusercontent.com/34116562/81773456-e9e9a500-9505-11ea-80b1-abd9c49830c2.png)
