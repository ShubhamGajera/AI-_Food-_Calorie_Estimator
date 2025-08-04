# 🍔 AI Food Calorie Estimator (Gemini 2.0 Flash)

### 📌 Project Overview

The **AI Food Calorie Estimator** is a web-based application that uses **Gemini 2.0 Flash API** to analyze food images.
It can:

* Detect whether an uploaded image is **food or not**.
* Estimate the **calories** of the food item.
* Provide **nutritional information** like carbs, protein, and fats.
* Give **health suggestions** about the food.

This project is **powered by Google’s Gemini API** and **Gradio** for creating a simple web interface.
Perfect for **class submission** and **AI/ML demonstrations**.

---

### 🚀 Features

* ✅ **Food Recognition** – Detects if the uploaded image is a food item.
* ✅ **Calorie Estimation** – Gives approximate calorie count.
* ✅ **Nutritional Details** – Basic info like protein, carbs, and fat content.
* ✅ **Health Suggestions** – Tells if the food is healthy or should be eaten in moderation.
* ✅ **Error Handling** – Shows an error if the image is not food.

---

### 🛠️ Tech Stack

* **Python 3.9+**
* **Gradio** (Web Interface)
* **Pillow (PIL)** (Image Handling)
* **Requests** (API Calls)
* **Gemini 2.0 Flash API** (Food Analysis)

---

### 📂 Project Structure

```
AI-Food-Calorie-Estimator/
│
├── AI_Food_Calorie_Estimator.ipynb             # Main Python file with Gradio app
├── README.md                                   # Project documentation
```

---

### ⚡ How It Works

1. **User uploads a food image** in the Gradio interface.
2. **Gemini API** analyzes the image:

   * If **not food →** returns an error.
   * If **food →** returns:

     * Food Name
     * Estimated Calories
     * Nutritional Details
     * Health Tips
3. **Results are displayed** in a formatted text box.

---



### 🔑 API Key Setup

* This project uses **Google Gemini 2.0 Flash API**.
* Replace `GEMINI_API_KEY` in `AI_Food_Calorie_Estimator.ipynb` with your own API key:

```python
GEMINI_API_KEY = "YOUR_API_KEY_HERE"
```

---

### 👨‍💻 Author

**Shubham Gajera**
📧 Email: `shubhamgajera122@gmail.com`

---


<!-- SHUBHAM GAJERA -->
