﻿ReadMe

All the coding has been done in python. I have used pandas dataframe to access the contents of the csv file. Flask along with HTML and JavaScript is used to make the web application.

    1. Clone this repository
    2. Create a virtual environment by running the following commands-
        i. virtualenv -p /usr/bin/python3 venv
        ii. source venv/bin/activate
        iii. pip install -r requirements.txt
        iv. python flask_app.py
        v. Open the link on a web browser
        vi. Enter the url you wish to find the flair for.

File Descriptions
    1. getData_reddit.py : Python script that gets the data from submissions from reddit from the subreddit India and enters it into a csv
    2. initial_final.csv : Stores the above mentioned data for 100 submissions
    3. initial_final_10000.csv : Stores the above mentioned data for 10000 submissions
    4. cleaning.py : Python script that cleans the data that we get from reddit
    5. getCleanData.py : Python script that calls the function from above mentioned file and stores the cleaned data in a csv
    6. cleaned_data_final : Stores the above mentioned data for 100 submissions
    7. cleaned_data_final_10000.csv : Stores the above mentioned data for 10000 submissions
    8. ml_model_combined_prereg.py : Python script that performs logistic regression(Machine Learning) for the fields of title, url, comments, author and id to get results for the flair
    9. log_reg_combined_model.sav : Model obtained from the above mentioned for 100 submissions
    10. log_reg_combined_model_10000.sav : Model obtained from the above mentioned for 10000 submissions
    11. flask_app.py : Runs the python web application
    12. Templates : contains the HTML files
    13. Static : contains the CSS files
