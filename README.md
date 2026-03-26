# 🌿 PlantScan AI

A beautiful Streamlit web application that uses AI to identify plants from photos and provide detailed analysis including health status, garden suitability, and pollinator impact.

![PlantScan AI](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-FF6B6B?style=for-the-badge)

## ✨ Features

- 🌱 **Instant Plant Identification** - Upload any plant photo and get AI-powered identification
- 🩺 **Health Analysis** - Detect if your plant is healthy, stressed, or diseased
- 🌻 **Garden Suitability** - Learn if the plant is suitable for your garden
- 🐝 **Pollinator Impact** - Discover how the plant affects bees and other pollinators
- 📜 **Scan History** - Keep track of all your plant scans with search functionality
- 🍃 **Beautiful UI** - Animated falling leaves with a nature-inspired design

## 🚀 Live Demo

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](YOUR_STREAMLIT_CLOUD_URL_HERE)

## 📦 Installation

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/plantscan-ai.git
cd plantscan-ai
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up your Groq API key:
```bash
export GROQ_API_KEY="your-api-key-here"
```

5. Run the app:
```bash
streamlit run app.py
```

## 🌐 Deploy to Streamlit Cloud

### Step 1: Push to GitHub

1. Create a new repository on GitHub
2. Push your code:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/plantscan-ai.git
git push -u origin main
```

### Step 2: Deploy on Streamlit Cloud

1. Go to [Streamlit Cloud](https://streamlit.io/cloud)
2. Sign in with your GitHub account
3. Click **"New app"**
4. Select your repository
5. Set the main file path to `app.py`
6. Click **"Advanced settings"** and add your secrets:
   - Key: `GROQ_API_KEY`
   - Value: Your Groq API key
7. Click **"Deploy"**

Your app will be live in minutes! 🎉

## 🔑 Getting a Groq API Key

1. Go to [console.groq.com](https://console.groq.com)
2. Sign up for a free account
3. Navigate to **API Keys**
4. Create a new API key
5. Copy and save it securely

## 📁 Project Structure

```
plantscan-ai/
├── app.py                 # Main Streamlit application
├── requirements.txt       # Python dependencies
├── .gitignore            # Git ignore rules
├── .streamlit/
│   └── secrets.toml      # Local secrets (not in git)
└── README.md             # This file
```

## 🛠️ Technologies Used

- **Streamlit** - Web app framework
- **Groq API** - AI model for plant analysis (Llama 4 Scout)
- **Pillow** - Image processing
- **Python** - Backend logic

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built with ❤️ using [Streamlit](https://streamlit.io)
- Powered by [Groq](https://groq.com) AI

---

Made with 🌿 by [Your Name]
