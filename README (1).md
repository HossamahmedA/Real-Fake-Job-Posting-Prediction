
![Logo](https://upload.wikimedia.org/wikipedia/commons/7/7c/Kaggle_logo.png)


# Real Fake Job Posting Prediction


This dataset contains 18K job descriptions out of which about 800 are fake. The data consists of both textual information and meta-information about the jobs.
The dataset can be used to create classification models which can learn the job descriptions which are fraudulent.
The dataset is very valuable as it can be used to answer the following questions:

1-Create a classification model that uses text data features and meta-features and predict which job description are fraudulent or real.

2-Identify key traits/features (words, entities, phrases) of job descriptions which are fraudulent in nature.

3-Run a contextual embedding model to identify the most similar job descriptions.

4-Perform Exploratory Data Analysis on the dataset to identify interesting insights from this dataset.

This project uses data from Kaggle.

## Features

#### Get all items



| feature | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `job_id` | `int64` | 'Unique Job ID' |
| `title` | `object` | 'The title of the job ad entry.' |
| `location` | `object` | 'Geographical location of the job ad.' |
| `department` | `object` | 'Corporate department (e.g. sales).' |
| `salary_range` | `object` | 'Indicative salary range (e.g. $50,000-$60,000)' |
| `company_profile` | `object` | 'A brief company description.' |
| `requirements` | `object` | 'The details description of the job ad.' |
| `benefits` | `object` | 'Enlisted requirements for the job opening.' |
| `telecommuting` | `int64` | 'Enlisted offered benefits by the employer.' |
| `has_company_logo` | `int64` | 'True for telecommuting positions.' |
| `has_questions` | `int64` | 'If this company has any questions for you' |
| `required_experience` | `object` | 'Required experience ' |
| `required_education` | `object` | 'Unique Job ID' |
| `industry` | `object` | 'industry of this company' |
| `function` | `object` | 'function you will do' |
| `fraudulent` | `int64` | 'Is This Job Real or Fake?' |




