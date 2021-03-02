# Project-4-NLP-unsupervised--Google-application-review
Project 4 NLP unsupervised- Google application review <br/>

Description: As an app developer, we work hard to create application and strive to get as many five-star reviews as possible. However, earning perfect review is not critical for future development. In fact, negative reviews can actually help us to improve our application. The goal of this project is to find out:
- What topic has been discussed?
- Any specific problem or issue users has mentioned?
<br/><br/>

Data source from Kaggle: <br/>
Google apps reviews  https://www.kaggle.com/tiquasar/playstore-reviews-google-apps?select=app_details.csv<br/>

1. app_detail.csv <br/>

| Variable | Description                 | unique Value |
| -------- | -----------                 | ------------ |
| Title    | Name of the app             | 82           |
| summary  | description of the App      | 82           |
| installs | number of Installs          | --- |
| Score    | User rating of the App      | 1-5 Star     |
| ratings  | Playstore rating of the App | --- |
| reviews  | number of reviews           | --- |
| appid.   | use to merge dataset        | --- |

2. Playstore_Google_Apps_User_Reviews.csv <br/>

| Variable | Description                          | unique Value |
| -------- | -----------                          | ------------ |
| Content  | Review of the App                    | 95004        |
| score    | Rating given by the user for the App | 1-5 Star |
| at       | Time of Review Creation              | --- |
| appid    | use to merge dataset                 | --- |
   

Methods: NLP, Sentiment, Topic Model(LDA/NMF/LSA), cluster (Kmeans)<br/><br/>
Tools Used:
- Pandas
- Numpy
- Pickle
- Matplotlib
- Seaborn
- Scipy
- Sklearn (scikit-learn)
- NLTK

