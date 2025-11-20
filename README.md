# YouTube-Transcript-Summarizer-Quick-Insights
This project allows you to fetch YouTube video transcripts and generate concise summaries instantly. Powered by Facebook BART for summarization and FastAPI for serving endpoints, it turns long video content into digestible insights—perfect for research, learning, or content review.
# 🎥 Video Preview
[UI](https://github.com/user-attachments/assets/36fb59cf-c9f7-4007-b706-fc0f85e20505)
# 🛠 Features

Extracts YouTube video transcripts automatically.

Summarizes long transcripts into short, readable summaries.

REST API endpoint to integrate with other applications.

Secure access with API Key authorization.

Quick deployment using Ngrok for instant public URLs.

# ⚡ Installation & Setup
# Install dependencies
pip install protobuf==3.20.*
pip install transformers
pip install youtube-transcript-api
pip install pyngrok
pip install fastapi uvicorn


Replace NGROK_TOKEN and API_KEY in the script with your own credentials.

Run the FastAPI app:

python app.py


Ngrok will provide a public URL to access the /summarize endpoint.

# 🧰 Technologies Used

Python 3.11

Transformers (BART Large CNN) – Text summarization

FastAPI – REST API

Ngrok – Public tunnel for local servers

YouTube Transcript API – Fetch video transcripts

# 💡 How It Works

User provides a YouTube video URL.

Video ID is extracted from the URL.

Transcript is fetched using YouTubeTranscriptApi.

Transcript is summarized using BART summarizer.

Summary is returned via a REST API response.

# 📈 Why Use This?

Save time by reading summaries instead of full videos.

Integrate into your own apps for automated content analysis.

Learn or research efficiently with fast textual insights.

# 🔐 Security

API requests require a valid Authorization header (Bearer API_KEY).

Supports safe, temporary public URLs via Ngrok for easy sharing.

# 🎯 Next Steps / Enhancements

Add multi-language support for transcripts.

Improve summary with custom length and style options.

Add a web interface using Streamlit or React.

# 📌 License

This project is MIT licensed – free to use and modify.

This README will make your GitHub repo look professional, easy to understand, and visually appealing.
