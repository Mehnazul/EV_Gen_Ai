# 🚗 AI-Powered Route & Charging Optimization for Electric Vehicles

Hey everyone 👋  
This is my project for the **AICTE – Edunet Foundation Skills4Future Internship** under the *Electric Vehicle* theme with *Generative AI* as the core technology.

---

## 🔋 About the Project

We all know how EV users often worry about battery range and where to charge next.  
So, I built a simple project that uses **Generative AI** to suggest optimized travel routes between cities and also shows **real EV charging stations across India** on an interactive map.  

The idea is to reduce “range anxiety” and make EV travel planning smarter and easier.

---

## 🎯 What This Project Does

1. Loads a dataset of real EV charging stations in India (`ev-charging-stations-india.csv`).
2. Visualizes the first 100+ charging stations on an interactive **Folium map** of India.
3. Uses the **GPT-2 Medium** model from Hugging Face to generate AI-based route suggestions.
4. Example:  
   > “From Chennai to Coimbatore — Start with 80% charge, stop at Vellore EV Charger after 210 km, recharge for 25 minutes, then continue your trip.”

---

## ⚙️ Tech Stack Used

- **Python**  
- **Google Colab / Jupyter Notebook**  
- **Pandas** – to handle the dataset  
- **Folium** – for interactive maps  
- **Transformers (GPT-2 Medium)** – for text generation  
- **Torch & Geopy** – for model and distance handling

---

## 📂 Files in This Repository

| File | Description |
|------|--------------|
| `EV.ipynb` | Main notebook (contains dataset loading, map, and AI route generation). |
| `ev-charging-stations-india.csv` | Dataset of EV charging stations across India. |

---

## 📊 Results

✅ Interactive map showing EV stations across India.  
✅ Generative AI route suggestions between cities.  
✅ Simple and working example of how AI can make EV driving easier.

---

## 🚀 Future Ideas

- Add live distance data using Google Maps API.  
- Predict energy usage using ML.  
- Turn this into a Streamlit web app.  

---

## ✨ Credits

**Created by:** *Mehnaz Ul Ain*  
**Internship:** AICTE – Edunet Foundation (Skills4Future 2025)  
**Project:** AI-Powered Route & Charging Optimization for EVs  
**Tools Used:** Python, Folium, Hugging Face GPT-2

---

Thanks for checking out my project 🙌  
Feel free to explore, fork, or suggest improvements!
