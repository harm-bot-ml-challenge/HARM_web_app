# HARM - ML Challenge

HARM, a ThinkBeyondExams intern team, aims to expand the world of AI with a little step of providing users a feature which shows the category of a YouTube video currently played.

Using the Python programming language and various Machine Learning concepts to create a Text classification and Image classification model which classifies a YouTube Video as Educational and cat- egorises it under category and sub-category as per the categories list of Beyond Exams Website.


## Problem Statement
A) Given a Youtube video:
1. Determine if it is an educational video or not.
2. Determine which category or subcategory of Beyon- dExam would it belong to.  

B) Accuracy: 90percent on custom dataset that will be provided after proof of concept.  
C) Should be able to run in near-real-time on a server.  

## Which tech stack or tools are we using?
```
scikit-learn
bokeh
chime
matplotlib
nltk
numpy
pandas
Pillow
pytube
requests
scikit_image
stqdm
streamlit
streamlit_player
toml
youtube_search_python
scrapetube
youtube-dl
tensorflow
keras
ludwig
```

## How much we have implemented and will be implementing?
- Built a real world Web Application, which takes an input of a YouTube Video URL and runs our models and algorithms of fetching and showcasing the information on it.
- Made a dataset generation file, which generates the dataset as per our requirements.
- Made the model files, to run it on the datasets generated.
- About to practice and apply our knowledge to enhance the User experience of our website and market the website to get it reach out to more and more audience.

## Live demo link and the Video demo
[Github Project Link](https://github.com/repository_invitations/195771281/accept)  
[Demo Link](https://huggingface.co/spaces/HarshulNanda/HARM_ML_App_ludwig)  
[Video Demo Link](https://drive.google.com/file/d/1HAHv_opmFJMg6x0QkNskN0S2eVQM4NyZ/view?usp=share_link) 

## How do we plan to work on the remarks provided in the ideation stage evaluation?
- Updating the Readme.md file as per guidelines.
- Editing the new demo video file for our project.

## Are we facing any issues?
- Till now not faced any big problems, everything is going as planned. Hope of that in future too.

## Project Members with their contributions to this project

1. __Harshul Nanda__ - Web hosting, Image and Text Dataset Generation

2. __Abhijeet Saroha__ - Streamlit and Web Development 

3. __Rishabh Sagar__ - Image processing and Image classification model

4. __Mayank Arora__ - Textual data processing and Text classification model

## Why this project is different from other ones? What unique features does this project have?
Our HARM website provides the following features which makes it different from other projects.
- User can get the prediction of whether a YouTube video is educational or non educational by entering the Youtube video url. If the video is educational, we apply category and sub-category model as per the problem statement returning the probability percentage bar graph 📊 of the predictions.
- User can get the channel statistics (custom number of top videos of a channel) by entering the any of that channel's video link. The channel statistics are in the form of a dataframe with attributes including title, description, original category, educational or not and predicted category by our model.
- User can also search results for custom number of videos by entering the keyword in the text field and get the prediction as per the problem statement of each of the video searched.
- User can get the prediction graph as mentioned before of all the videos in a YouTube playlist by just entering the Playlist URL.
- We also provide a feature which apply our education or non educational classification model to each of the dialogues of a video (of which subtitles are available), predicting the percentage of Educational content that video provides.
