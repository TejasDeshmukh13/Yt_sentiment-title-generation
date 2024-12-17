
# 🎥 **YouTube Sentiment Analyser and Title Generator** 

## **Overview**  
Welcome to the **YouTube Sentiment Analyser and Title Generator** project! This web-based application leverages **Natural Language Processing (NLP)** to analyze YouTube video comments for sentiment, generate optimized video titles, and summarize video transcripts. The tool helps enhance YouTube content by providing insights and recommendations.

### **Key Features** 🚀  
1. **YouTube Video Sentiment Analysis**  
   - Analyze the sentiment of comments (positive, negative, neutral) on any YouTube video.  

2. **Title Recommendation**  
   - Generate optimized, catchy YouTube titles based on the video's content.  

3. **Transcript Summarization**  
   - Summarize the YouTube video's transcript into a concise overview of the content.  

4. **Channel Statistics**  
   - Retrieve and display channel statistics like total views, subscriber count, and more.  
   - 📊 **Try it now**: 

5. **Real-time Data Fetching**  
   - Fetch up-to-date data directly from the YouTube Data API for accurate results.  
   - 🔄 **Real-time Updates**: Always accurate with the latest data.

---

## **Objectives** 🎯

The primary objectives of this project are:
1. **Sentiment Analysis of YouTube Comments**  
   - To provide insights into the overall mood (positive, negative, neutral) of comments on YouTube videos. This helps content creators understand their audience's reaction and engagement.
   
2. **Title Generation for YouTube Videos**  
   - To automatically generate optimized video titles using NLP models, improving click-through rates and engagement on YouTube videos.
   
3. **Summarization of YouTube Video Transcripts**  
   - To provide a summarized version of YouTube video transcripts, making it easier for viewers to quickly grasp the content.

4. **Channel Statistics Analysis**  
   - To fetch and display channel statistics, enabling YouTubers to track their growth and performance more effectively.

---

## **Installation** 🛠️

### **Prerequisites**  
Ensure the following dependencies are installed before setting up:
- **Python 3.x**
- **Flask**: Web framework to build the application.
- **MySQL**: For storing user and video data.
- **YouTube Data API Key**: Required to fetch data from YouTube.
- **Hugging Face Transformers**: For advanced NLP models.
- **Jinja2**: HTML templating engine.
- **Chart.js**: For generating charts (sentiment analysis distribution).

### **Steps to Set Up**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/TejasDeshmukh13/Yt_sentiment-title-generation.git
   cd Yt_sentiment-title-generation
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables:**
   - Create a `.env` file in the project root and add:
   ```bash
   YOUTUBE_API_KEY='your_api_key_here'
   ```

4. **Run the Flask app:**
   ```bash
   python app.py
   ```

5. **Visit the app in your browser:**
   - Go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/) to access the web application.

---

## **Usage** 💡

### **Sentiment Analysis** 📝  
1. **Input**: Enter the **YouTube video URL**.  
2. **Functionality**: The app will:
   - Fetch comments from the YouTube video.
   - Analyze the sentiment of each comment (positive, negative, or neutral).
   - Display a sentiment distribution chart.
3. **Output**: A visual representation of sentiment (positive, negative, neutral).  
   🔍 **Try it now**: Enter a video URL for sentiment analysis!

### **Title Generation** 🏷️  
1. **Input**: Enter the **YouTube video URL** (same as sentiment analysis).  
2. **Functionality**: The app will:
   - Generate optimized titles using the trained NLP model (T5 model).
   - Display suggested titles tailored to the video's content.
3. **Output**: A list of recommended titles for the video.  
   🏷️ **Try it now**: Enter a video URL for title generation!

### **Transcript Summarization** 🧠  
1. **Input**: Enter the **YouTube video URL**.
2. **Functionality**: The app will:
   - Fetch and summarize the transcript of the YouTube video.
   - Provide a concise summary, focusing on key points.
3. **Output**: A summary of the video transcript.  
   🧠 **Try it now**: Enter a video URL to get the summary!

### **Channel Statistics** 📊  
1. **Input**: Enter the **YouTube channel ID** or URL.
2. **Functionality**: The app will:
   - Fetch channel details like total views, subscriber count, and more.
   - Display detailed channel statistics.
3. **Output**: Channel stats, including views, subscribers, and more.  
   📊 **Try it now**: Enter a channel ID to fetch statistics!

---

## **📂 Implementation Features** 

### **System Architecture** 

![image alt](https://github.com/TejasDeshmukh13/Yt_sentiment-title-generation/blob/565a8a5023ba8f14e380d7344b558e3a1381f2e2/senti/Picture1.png)


## **Designs**0)

1.Dashboard

![image alt](https://github.com/TejasDeshmukh13/Yt_sentiment-title-generation/blob/565a8a5023ba8f14e380d7344b558e3a1381f2e2/senti/Picture2.jpg)

2.YouTube Sentiment Analysis
![image alt](https://github.com/TejasDeshmukh13/Yt_sentiment-title-generation/blob/565a8a5023ba8f14e380d7344b558e3a1381f2e2/senti/Picture4.png)
![image alt](https://github.com/TejasDeshmukh13/Yt_sentiment-title-generation/blob/565a8a5023ba8f14e380d7344b558e3a1381f2e2/senti/Picture5.png)
![image alt](https://github.com/TejasDeshmukh13/Yt_sentiment-title-generation/blob/565a8a5023ba8f14e380d7344b558e3a1381f2e2/senti/Picture6.png)

3.Channel Statistics
![image alt](https://github.com/TejasDeshmukh13/Yt_sentiment-title-generation/blob/565a8a5023ba8f14e380d7344b558e3a1381f2e2/senti/Picture7.png)
![image alt](https://github.com/TejasDeshmukh13/Yt_sentiment-title-generation/blob/565a8a5023ba8f14e380d7344b558e3a1381f2e2/senti/Picture8.png)
![image alt](https://github.com/TejasDeshmukh13/Yt_sentiment-title-generation/blob/565a8a5023ba8f14e380d7344b558e3a1381f2e2/senti/Picture9.png)

4.Youtube Transcript Summarizer
![image alt](https://github.com/TejasDeshmukh13/Yt_sentiment-title-generation/blob/565a8a5023ba8f14e380d7344b558e3a1381f2e2/senti/Picture10.jpg)

5.Youtube Title Generator
![image alt](https://github.com/TejasDeshmukh13/Yt_sentiment-title-generation/blob/565a8a5023ba8f14e380d7344b558e3a1381f2e2/senti/Picture11.jpg)








---



