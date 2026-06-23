# 🎓 AI-Powered Course Recommendation System

<p align="center">
  <b>Discover the perfect course with Machine Learning-driven recommendations.</b>
</p>

<p align="center">
  Built using Python • Scikit-Learn • Streamlit • Docker
</p>

---

## 📖 About The Project

Choosing the right online course from thousands of available options can be challenging. This project solves that problem by leveraging **Machine Learning** and **Natural Language Processing (NLP)** to recommend courses that closely match a user's interests.

The system analyzes course titles, descriptions, and skills from a dataset containing **3,000+ Coursera courses** and generates personalized recommendations using **text vectorization** and **cosine similarity**.

Whether you're exploring Data Science, Machine Learning, Programming, Business, or Design, the recommendation engine helps users discover relevant learning opportunities instantly.

---

## ✨ Key Features

🔹 Intelligent course recommendation engine

🔹 NLP-based text processing and feature extraction

🔹 Similarity matching using Cosine Similarity

🔹 Interactive Streamlit web application

🔹 Fast recommendation generation

🔹 Dockerized deployment support

🔹 Scalable and easy-to-maintain architecture

---

## 🧠 How It Works

```text
Course Dataset
      │
      ▼
Data Cleaning & Preprocessing
      │
      ▼
Feature Engineering
(Course Name + Skills + Description)
      │
      ▼
Text Vectorization
      │
      ▼
Cosine Similarity Matrix
      │
      ▼
Recommendation Engine
      │
      ▼
Top Relevant Courses
```

---

## 🛠️ Tech Stack

| Technology   | Purpose              |
| ------------ | -------------------- |
| Python       | Core Development     |
| Pandas       | Data Processing      |
| NumPy        | Numerical Operations |
| Scikit-Learn | Machine Learning     |
| Streamlit    | Web Application      |
| Pickle       | Model Serialization  |
| Docker       | Containerization     |

---

## 📂 Project Structure

```bash
Course-Recommendation-System/
│
├── Data/
│   └── Coursera.csv
│
├── models/
│   ├── courses.pkl
│   └── course_list.pkl
│
├── CourseRecommendationSystem.py
├── main.py
├── requirements.txt
├── Dockerfile
└── README.md
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/bandisaisripraneeth/Course-Recommendation-System.git

cd Course-Recommendation-System
```

### Create a Virtual Environment

#### Windows

```bash
python -m venv env
env\Scripts\activate
```

#### Linux / macOS

```bash
python -m venv env
source env/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

### Generate Recommendation Data

```bash
python CourseRecommendationSystem.py
```

### Launch Streamlit App

```bash
streamlit run main.py
```

### Open in Browser

```text
http://localhost:8501
```

---

## 🐳 Docker Support

### Pull Image

```bash
docker pull bandisaisripraneeth/course-recommendation-system:latest
```

### Run Container

```bash
docker run -p 8501:8501 bandisaisripraneeth/course-recommendation-system:latest
```

### Access Application

```text
http://localhost:8501
```

---

## 📈 Recommendation Methodology

The recommendation system follows a content-based filtering approach:

1. Extract relevant course information
2. Perform text preprocessing
3. Convert textual data into numerical vectors
4. Calculate pairwise cosine similarity
5. Identify the most relevant courses
6. Return top recommendations to the user

This approach enables accurate recommendations without requiring user history or ratings.

---

## 🎯 Future Improvements

* Personalized user profiles
* Deep Learning embeddings (BERT/Sentence Transformers)
* Course rating integration
* Learning path generation
* Multi-platform course recommendations
* Cloud deployment on AWS/GCP

---

## 👨‍💻 Author

### Bandi Sai Sri Praneeth

Backend Developer | Machine Learning Enthusiast | Research Aspirant

* Passionate about Machine Learning, NLP, and Data Science
* Building intelligent recommendation systems and AI applications
* Exploring emerging technologies and research-driven solutions

GitHub: [https://github.com/bandisaisripraneeth](https://github.com/Saipraneeth13)

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature/new-feature
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push to GitHub

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

## ⭐ Support

If you found this project useful:

⭐ Star the repository

🍴 Fork and contribute

📢 Share it with others

---

### Built with ❤️ by Bandi Sai Sri Praneeth
