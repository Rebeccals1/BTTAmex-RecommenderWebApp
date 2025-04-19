# American Express: Attentive Recommendation Web Application
Break Through Tech is an organization that tries to empower many diverse students. They do this by having students participate in a year long program designed to teach them all about Machine Learning. In this program, our goal was to make a two-tower recommendation model. To help guide us through this process, our team collaborated with an American Express Advisor.

As a side project, I created this simple web application to help showcase the teams ML model. This application displays a list of mock users. Then, when a name is clicked, it takes you to a profile page where it will display the User ID, image and purchased history. After some time, it will then load a list of up to five recommended products based upon the user's id number and purchased history.

For more information about the Two-Tower Recommendation model itself, you can find the original repository here: https://github.com/ardahk/amex.

---

## 🚀 Features

- Dynamic user profile generation with images and metadata
- AI-based product recommendation system using a Two-Tower model
- Real-time inference using TensorFlow and preprocessed datasets
- Data loaded from CSVs
- Interactive, responsive web app built with Streamlit
- Multi-page navigation using query parameters
- Gender-based profile image selection and display

---

## 🧠 How It Works

1. **Random user profiles** are generated with gender, image, and user ID.
2. On clicking a user, a **personalized page** displays product recommendations.
3. The recommendation system loads user-product vectors and scores product matches using **dot product similarity**.
4. Products are sorted and displayed dynamically in the user interface.

---

## 🛠️ Tech Stack

- **Frontend:** Streamlit
- **Backend/ML:** Python, TensorFlow, Pandas
- **Data:** GitHub-hosted CSVs
- **Storage:** JSON session files & local image directory

---

## 📦 Installation

```bash
git clone https://github.com/your-username/BTTAmexWebApp.git
cd BTTAmexWebApp
pip install -r requirements.txt
streamlit run app.py
```

---

## 🔐 Optional: Using Supabase as a Backend

This project can be extended with [Supabase](https://supabase.io) to:
- Replace static CSVs with real-time Postgres queries
- Store user sessions or ratings
- Manage profile images in storage buckets


## 📄 License

This project is licensed under the MIT License.
