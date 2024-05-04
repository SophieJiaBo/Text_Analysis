# Text_Analysis
This project analyzes queen's song lyrics and the sentiments of the lyrics. I chose the dataset from the Kaggle website (https://www.kaggle.com/datasets/tongthongsa/queen-hit-songs-lyrics), uploaded and updated by TONGTHONGSA. This dataset contains information about Queen's song lyrics, originally gathered from the Genius website (https://genius.com/). This dataset includes songs like Under Pressure, Somebody to Love, etc. This dataset has five variables, such as album names ('album'), song titles ('track_title'), song lyrics (lyric), etc., and 612 observations. In this case, this dataset helps provide insights into the information of Queen's songs, their frequently used words and lyrics' sentiments in particular.

I'm analyzing this dataset because I'm a fan of Queen, and I'm curious about exploring Queen's lyrics and styles through data science methods and learning about the sentiments behind their songs. Therefore, I'll focus on the song lyrics variable ("lyric") contained in this dataset. The song lyrics ("lyric") here are text data that is comprised of words. 

I have two research questions: 
- What types of words are most frequently used in Queen's songs?
- What kinds of sentiments are more connected with their songs? 

# Results
I visualized the frequently used words and analyzed and visualized the sentiments behind each song. For the frequently used words besides what I already talked about in the previous section, some other frequently used words include "free," crazy," alive," stop," etc. This further shows that most words used in Queen's songs are pretty simple words that we'll use in our everyday lives. This answers my first research question.

Besides, I used a sentiment dictionary from nrc, which makes association between words and emotions of anger, anticipation, disgust, fear, etc. By using the sentiment package from NRC, I calculate the sentiments connected with each song. According to the figure above, generally, Queen's songs show mostly positive-related feelings and very few negative-related feelings. Moreover, I observed that there are very low levels of disgust-related feelings and sad-related feelings in these songs.

For the second sentiment analysis, I used the sentiment dictionary from bing. This dictionary makes association between words and emotions of positive and negative. According to the results, although some songs obtain more positivity than negativity and vice versa, overall, across all songs, there's a balance between positive and negative emotions. Both of these sentiment analysis answer my second research question.

Comparing these two dictionaries, I come to know the consequences behind each dictionary. For the NRC dictionary, while it provides specific emotion associations such as anger and anticipation, it may make mistakes in properly assigning the words with emotions. For example, looking at specific word-emotion associations in the NRC dictionary, I find that the word "money" is associated with feelings of anger, anticipation, joy, surprise, trust, and positivity at the same time, which sounds not accurate enough. For the Bing dictionary, while it only assigns words with two different feelings (positive or negative), it does make more accurate judgments when we look at the specific word-emotion association. In this case, the consequence of the nrc dictionary is a potential lack of accuracy, and the consequence of the Bing dictionary is a lack of specific emotions.

<img width="400" alt="image" src="https://github.com/SophieJiaBo/Text_Analysis/assets/168926944/ea4afda4-9122-4251-b4cf-809db6105b83">
<img width="519" alt="image" src="https://github.com/SophieJiaBo/Text_Analysis/assets/168926944/78f0c247-ad98-4bd9-ae91-0323e8d24ed1">
<img width="504" alt="image" src="https://github.com/SophieJiaBo/Text_Analysis/assets/168926944/5e15daa1-985e-4be4-929c-22fa227f60c9">
<img width="521" alt="image" src="https://github.com/SophieJiaBo/Text_Analysis/assets/168926944/01e8619e-55d2-4159-ac2f-893411ddd493">



