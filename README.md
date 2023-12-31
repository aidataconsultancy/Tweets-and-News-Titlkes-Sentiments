# Tweets-and-News-Titles-Sentiment-Analysis-using-Streamlit-App

Before you begin, please make sure to review the prerequisites for running Streamlit on your local machine. Additionally, you will need an API key from OpenAI in order to use the DALLE image generation model.

```ruby

# create a virtual environment
cd work dir
python3.9 -m venv streamlit_venv
source streamlit_venv/bin/activate


# install requirements.txt
cd [where requirements.txt is]
pip install -r requirements.txt


# Run the streamlit app and show on local browser:
streamlit run appname.py

```

The "app.py" file is located in the "experiments" folder. Change your directory to "experiments" to run the app. 

This is how the application appears: you have the ability to upload a CSV file that has a "text" column. This allows two models, FinBERT and RoBERTa, to analyze the tweets within that column and predict their sentiments and probability. A pie chart is used to display the count of each sentiment, allowing you to determine which sentiment occupies the largest proportion of your dataset. Alternatively, you can indicate the path of your CSV file within the "app.py" file, located in the "experiments" folder.

<img width="1182" alt="Screenshot 2023-03-21 at 5 21 29 PM" src="https://user-images.githubusercontent.com/88580416/226578371-d382667f-7da6-46f2-9176-304e4a0efa40.png">

In case you encounter any nonsensical outcomes, you have the option of copying and pasting the text into the input box. This will enable the prediction of sentiment scores for each label, alongside their corresponding probability score.

<img width="1174" alt="Screenshot 2023-03-21 at 5 21 47 PM" src="https://user-images.githubusercontent.com/88580416/226578423-c3b5e9ce-976d-44b3-a3af-e1bcf4938064.png">

Both models can also be employed for predicting sentiments on news headlines. To do so, you can either upload a CSV file with a "title" column or specify the CSV file path directly within the "app.py" file located in the "experiments" folder.

<img width="1181" alt="Screenshot 2023-03-21 at 5 22 03 PM" src="https://user-images.githubusercontent.com/88580416/226578462-6af45934-1c6c-481e-9359-92eed52d9ee6.png">

If the sentiment prediction appears nonsensical, try analyzing the text separately.

<img width="1177" alt="Screenshot 2023-03-21 at 5 22 20 PM" src="https://user-images.githubusercontent.com/88580416/226578488-16f6c305-0e7d-4725-ba0f-f414948b2249.png">

In addition, you can create an image from the news titles or tweets by inputting the text in the textbox. The OpenAI DALL-E API has been integrated for this purpose.

<img width="1176" alt="Screenshot 2023-03-21 at 5 22 42 PM" src="https://user-images.githubusercontent.com/88580416/226578518-90bfd01b-8710-4e2e-acb3-a1201024c204.png">

The results of the model will shown as below:

<img width="744" alt="Screenshot 2023-03-21 at 5 24 26 PM" src="https://user-images.githubusercontent.com/88580416/226583808-05f848a3-a7a4-4851-926e-96b70cff4247.png">
#   T w e e t s - a n d - N e w s - T i t l e s - S e n t i m e n t - A n a l y s i s - u s i n g - S t r e a m l i t - A p p - m a i n  
 