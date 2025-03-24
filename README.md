# Student Skill Gap Analysis & Recommendation System

## 📖 Project Overview
The **Student Skill Gap Analysis and Recommendation System** helps students assess their skills, identify gaps, and receive personalized recommendations for internships, learning resources, and career paths. The system leverages AI-powered analysis to provide insights based on user data.

## ✨ Features
- 📊 **Skill Analysis:** Visual representation of technical and soft skills.
- 🤖 **AI Career Chatbot:** Provides career guidance and answers student queries.
- 💼 **Internship Listings:** Displays internship opportunities based on skills.
- 📈 **Data Visualizations:** Generates insightful graphs for better understanding.
- 🛠 **Challenges & Support:** Offers solutions to common career-related challenges.
- 🔐 **Secure API Key Management:** Uses `.env` file to store API keys securely.

## 🛠 Tech Stack
- **Frontend:** Streamlit (Python-based UI)
- **Backend:** Python (Pandas, Matplotlib, Seaborn)
- **AI Model:** Hugging Face API (Falcon-7B)
- **Database:** CSV file (for dataset storage)
- **Environment Management:** `dotenv` (for secure API handling)

## 🚀 Installation Guide

### 🔹 Step 1: Clone the Repository
```sh
git clone https://github.com/yourusername/student-skill-gap-analysis.git
cd student-skill-gap-analysis
```

### 🔹 Step 2: Create a Virtual Environment
```sh
python -m venv env
source env/bin/activate  # On macOS/Linux
env\Scripts\activate    # On Windows
```

### 🔹 Step 3: Install Dependencies
```sh
pip install -r requirements.txt
```

### 🔹 Step 4: Set Up API Key
1. Create a `.env` file in the project root.
2. Add the following line inside `.env`:
```sh
HF_API_KEY=your_huggingface_api_key_here
```

### 🔹 Step 5: Run the Application
```sh
streamlit run app.py
```

## 📌 Usage
1. **Home Page** - Displays student details and skill insights.
2. **Skill Analysis** - Visualizes top skills and trends.
3. **Internship Listings** - Recommends internships.
4. **Career Chatbot** - Interact with AI chatbot.
5. **Challenges & Support** - Get solutions for common challenges.

## 📂 File Structure
```
student-skill-gap-analysis/
│-- app.py               # Main application file
│-- requirements.txt     # Dependencies list
│-- .env                 # API Key storage (not to be shared)
│-- dataset.csv          # Student skills dataset
│-- README.md            # Project documentation
│-- utils/
│   ├── chatbot.py       # Chatbot functions
│   ├── visualization.py # Data visualization functions
│   ├── preprocessing.py # Data processing utilities
```

## 🔐 Secure API Setup
To ensure security, API keys are stored in `.env` and loaded using:
```python
from dotenv import load_dotenv
import os
load_dotenv()
HF_API_KEY = os.getenv("HF_API_KEY")
```

## 🚀 Future Enhancements
- 🏆 **AI-based Skill Gap Prediction** using Machine Learning.
- 📢 **Personalized Course Recommendations**.
- 🏫 **Educator Dashboard** for academic institutions.
- 🔍 **Enhanced Internship Matching Algorithm**.

## 🤝 Contributing
Want to improve this project? Feel free to submit a pull request!

## 📞 Contact
For any queries or support, reach out at **support@skillgapanalysis.com**.

---
🔹 **Developed with ❤️ by Nehaa Acharya-Kanishka Verma-Yash Madaan-Shristi Saini**

