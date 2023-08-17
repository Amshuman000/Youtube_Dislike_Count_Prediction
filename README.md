# Youtube_Dislike_Count_Prediction
## YouTube video link as the input, predicts the number of dislikes in a YouTube video
This project involves predicting the number of dislikes a YouTube video might receive based on a provided YouTube video link. The process involves several steps:</br>

Data Gathering: The project collected real-time data from YouTube using the YouTube Data API. This data includes information such as the number of likes, comments, subscribers, and views for the given video.</br>

Model Training (Bi-LSTM NN): A Bidirectional Long Short-Term Memory Neural Network (Bi-LSTM NN) was trained using the gathered data. This model achieved an accuracy of 88% in predicting sentiment for IMDB movie reviews. This sentiment analysis model was adapted to handle YouTube comments, enabling it to understand the sentiment of comments on the video.</br>

Likes Prediction (SVM): A Support Vector Machine (SVM) was employed to predict the number of likes the YouTube video might receive. This model achieved an accuracy of 77% in predicting the likes count. Additionally, negative sentiments detected from the comments were taken into account as a factor contributing to predicting the dislikes count.</br>

Overall, this project combines sentiment analysis of YouTube comments with predictive modeling techniques to estimate the number of dislikes a given YouTube video might accumulate. The use of both the Bi-LSTM NN and SVM demonstrates the application of machine learning and natural language processing in understanding and predicting user engagement and sentiment on the platform</br>
