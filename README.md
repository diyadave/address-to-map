# address-to-map
A simple Python project to generate interactive maps from user-entered addresses using geopy and folium.
# 🗺️ Address to Interactive Map using Python

This is a simple Jupyter Notebook project that takes a user-input address and generates an **interactive map** with a marker using Python libraries.

---

## 🔧 Technologies Used

- 🧭 **Geopy** – To convert address into geographical coordinates (latitude & longitude)
- 🌍 **Folium** – To generate interactive maps with markers using Leaflet.js
- 📓 **Jupyter Notebook** – To write and run Python code in a notebook interface

---

## 🧠 How It Works

1. User enters any location (e.g., Surat, Eiffel Tower, New York).
2. The app uses **geopy** to convert the address into coordinates.
3. An interactive map is generated using **folium**, with a marker on the selected location.
4. If the address is not found, the map defaults to the **White House** in Washington D.C. 🏛️

---

## ▶️ Demo

> Coming soon!  
> You can run this notebook locally or try it on Google Colab.

---

## 📥 How to Run

1. Install the required libraries:

```bash
pip install geopy folium

Open the notebook in Jupyter:
jupyter notebook map_generator.ipynb
