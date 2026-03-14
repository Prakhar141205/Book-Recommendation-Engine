# 📚 Book Recommender System

A simple **machine learning based Book Recommender System** built using **Python, Flask, and collaborative filtering**.  
The application recommends books similar to a user-selected book based on similarity scores computed from user rating data.

---

# 🚀 Features

- Displays **popular books** on the homepage
- Allows users to **search for a book**
- Recommends **similar books using a similarity matrix**
- Shows **book title, author, and cover image**
- Simple **Flask web application**

---

# 🧠 How the Recommendation Works

The system uses **collaborative filtering** based on user ratings.

Steps:

1. A **pivot table (`pt.pkl`)** is created where  
   - Rows → Book titles  
   - Columns → Users  
   - Values → Ratings

2. A **similarity matrix (`similarity_scores.pkl`)** is computed using cosine similarity.

3. When a user enters a book:
   - The system finds its index in the pivot table
   - Retrieves the **top similar books**
   - Displays them on the webpage

---


---

## 🖥 Application Pages

### Home Page
Displays **popular books** with:

- Book title  
- Author name  
- Book cover image  
- Average rating  
- Number of ratings  

### Recommendation Page
Users can enter a **book title** and the system will recommend **similar books**.

---

## 📦 Technologies Used

- Python
- Flask
- NumPy
- Pandas
- Scikit-learn
- Pickle
- HTML
- CSS

---

## 📊 Dataset

The dataset includes:

- Books information
- User ratings
- Authors
- Book cover images

These are processed to generate the following files:


---

## 👨‍💻 Author

**Prakhar Sharma**

B.Tech CSE Student  
Aspiring Software Engineer | Open Source Enthusiast  

GitHub:  
https://github.com/Prakhar141205

---

## ⭐ Future Improvements

- Add **search autocomplete**
- Improve **recommendation accuracy**
- Deploy the project using **Docker**
- Add **user login system**
- Use **deep learning recommendation models**

---

Thankyou !
