# book-recommender-system
This book recommender system is designed using a hybrid approach that combines the advantages of both the popularity-based and collaborative filtering-based systems.
It uses exploratory data analysis to clean and preprocess the data and techniques like cosine similarity to provide personalized book recommendations based on user preferences, ratings, etc. By considering both popularity and collaborative filtering, the system is able to suggest a diverse range of books that are likely to be of interest to the user. All the steps including Data Preprocessing, EDA and the usage of similarity scores can be referred to in the "book-recommener-system.ipynb" file.

# Dataset used
https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset

## Demo Screenshots

![H6R5rSwZZe](https://user-images.githubusercontent.com/29508011/221418080-ce7ebe2e-0fba-4203-9a1b-5e68a1db311e.png)

![7zeMJXk9Jv](https://user-images.githubusercontent.com/29508011/221418095-3d2af1d3-12f6-4588-9bb0-963177f9ced5.png)

![RXKQHhsOW2](https://user-images.githubusercontent.com/29508011/221418104-293dde81-867f-43c7-af0f-8657262b7b88.png)

# Tech Stack
•	Front-End: HTML, CSS

•	Back-End: Flask

•	IDE: Jupyter Notebook, Pycharm

# How to run this app
1) Clone this repository

2) Create a virtual environment by using this series of commands:

 ----> pip install virtualenv > virtualenv myenv > myenv\Scripts\activate (for windows)

 ----> pip install virtualenv > virtualenv virtualenv_name > source virtualenv_name/bin/activate (for linux)

3) Copy all files from the cloned repo to newly created virtual environment folder.

4) Install all the packages by using the following command: pip install -r requirements.txt
 
5) Now for the final step. Run the app using this command: python app.py
