# YouTube Comment Sentiment Analysis Project

This project is a machine learning application designed to perform sentiment analysis on YouTube comments. It identifies whether comments are positive or negative, providing insights into public perception of video content.

## Technologies and Approach:

- **TensorFlow**: A powerful tool for building the machine learning model that classifies sentiments of comments.
- **YouTube API**: Enables the automatic fetching of comments from specified YouTube videos.
- **Flask**: Used to create web endpoints, making the application accessible via a web interface where users can input a video URL.
- **Numpy & Pandas**: Essential for data handling and analysis, facilitating the processing of comment data.
- **Matplotlib**: Allows for the visualization of analysis results, such as displaying the proportion of positive to negative comments in a graphical format.

## Workflow:

1. Users input a YouTube video URL through a simple HTML form on the Flask web interface.
2. The application retrieves comments for the video using the YouTube API.
3. These comments are then analyzed by the TensorFlow-based sentiment analysis model.
4. The application calculates and displays:
   - The total number of comments analyzed.
   - The number of positive and negative comments.
   - The positivity rate as a percentage.
5. For each comment, it indicates whether the sentiment was positive or negative.

This project effectively combines machine learning with web technologies to offer a user-friendly tool for sentiment analysis on YouTube comments, highlighting the application of AI in content evaluation.
