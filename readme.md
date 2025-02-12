# Flask AI-Powered News & Chatbot Project

## Project Overview
This is a Flask-based web application that integrates Google's Gemini AI for text and image processing and NewsAPI for fetching real-time technology and job-related news. The project provides AI-powered chatbot capabilities and news search functionalities.

## Features
- AI-powered chatbot using Google's Gemini API
- Real-time technology and job news aggregation
- News search functionality
- AI-based image processing and description generation
- User authentication pages (login, personal, about)

## Installation & Setup
### Prerequisites
Ensure you have Python installed on your system. You can download it from [Python's official website](https://www.python.org/downloads/).

### Step 1: Clone the Repository
```sh
git clone https://github.com/your-repo.git
cd your-repo
```

### Step 2: Create and Activate Virtual Environment
```sh
python -m venv myenv
# Activate virtual environment:
# Windows:
myenv\Scripts\activate
# macOS/Linux:
source myenv/bin/activate
```

### Step 3: Install Dependencies
```sh
pip install -r requirements.txt
```

### Step 4: Set Up Environment Variables
Create a `.env` file in the project root and add the following:
```
SECRET_KEY=your-secret-key-here
GOOGLE_API_KEY=your-google-api-key-here
NEWS_API_KEY=your-news-api-key-here
```

### Step 5: Run the Application
```sh
python app.py
```
The application will start in development mode. Open your browser and visit `http://127.0.0.1:5000/`.

## Project Structure
```
📂 project-root/
│── 📂 myenv/               # Virtual environment
│── 📂 static/              # Static files (CSS, JS)
│   ├── script.js          # JavaScript functions
│   ├── style.css          # CSS styles
│   ├── styles.css         # Additional CSS styles
│── 📂 templates/           # HTML templates
│   ├── about.html         # About page
│   ├── index.html         # Homepage
│   ├── login.html         # Login page
│   ├── personal.html      # Personal profile page
│   ├── realtime.html      # Real-time news page
│── 📂 uploads/             # Uploaded files (images)
│   ├── demo-image.jpg
│── app.py                 # Flask application
│── requirements.txt       # Required Python dependencies
│── .env                   # Environment variables (not in repo)
│── .gitignore             # Git ignore file
```

## API Integration
- **Google Gemini AI**: Used for generating text responses and processing images.
- **NewsAPI**: Fetches real-time tech and job news articles.

## License
This project is licensed under the MIT License.

## Author
Developed by [Karthik R C].
