# 🌿 PlanTonic - Houseplant Recognition & Care Guide App

PlanTonic is a mobile application that helps users **identify indoor ornamental plants** using a photo, and gives them **simple care tips** based on their needs.

It uses artificial intelligence to recognize plants, even when the user doesn't know their name. The goal is to make plant care easier and more enjoyable — especially for beginners!

---

## 📱 How It Works

1. 📷 Take or upload a photo of your plant
2. 🧠 The app identifies the plant species
3. 💧 You receive easy care instructions:
   - How much water it needs
   - Whether it likes sunlight or shade
   - Ideal temperature conditions

---

## 🧠 What’s Under the Hood (In Simple Terms)

This app uses a small, fast AI model trained to "look" at plant images and recognize which species they belong to.

- The model was trained using thousands of plant images.
- It can run directly on your phone (no internet needed).
- It doesn't collect or send any personal data — all recognition is done on the device.

Even though the AI part is complex, the **user experience is very simple**.

---

## 🎯 Why This App?

Many people buy houseplants, but they don’t know:

- What kind of plant it is
- How often to water it
- Why its leaves are turning yellow

PlanTonic solves this by combining **plant recognition** with **practical care suggestions**.

---

## 🖼️ Example Screenshots


| Plant Recognition | Care Suggestions |
|-------------------|------------------|
|<img width="237" alt="Screenshot 2025-06-27 at 19 43 43" src="https://github.com/user-attachments/assets/4b022979-4a7b-4987-851f-be33565cb4bd" /> | <img width="209" alt="Screenshot 2025-06-27 at 19 44 20" src="https://github.com/user-attachments/assets/093213b2-108f-498b-bb37-a049f2c97dc6" /> |


---

## 📂 Project Structure (For The Curious)
PlanTonic/
|-- model/           # AI models (plant + disease)
|-- images/          # Screenshots for README
|-- json/            # Mapping for plant names
|-- train.py         # AI training script
|-- test.py          # Optional testing script
`-- README.md        # This file

## 🏗️ System Overview

PlanTonic has 3 main parts:

1. **Mobile App** – where the user takes a photo
2. **Backend Server** – analyzes the image using AI
3. **AI Models** – recognize the plant, check for disease, and generate care tips

The app sends the photo to the server. The server runs two AI models:
- One to recognize the plant
- One to detect disease

Then it uses a language model (like ChatGPT) to create easy-to-understand advice.

---

## ⚠️ Limitations & Future Work

- Currently supports iOS only (Android version is planned)
- Works best with clear, close-up photos
- Requires internet connection for disease detection and care generation
- We plan to expand the plant and disease database in future versions

---

## ✅ Summary

PlanTonic is a blend of nature and technology. By turning a simple photo into knowledge, it helps people connect with their plants, take better care of them, and enjoy a greener life 🌿.

---

## 👥 Team

This project was developed as a Senior Project at Atılım University, Spring 2025.

Team Members:
- Atakan Apan
- Dilan Kaçar
- Ekin Çakmak
- Mehmed Emin Andaç
- Sarya Buluş
- Yalçın Yağız Korkmaz

Supervisor: Assoc. Prof. Dr. Cansu Çiğdem Ekin

---

## 📄 License

Open for non-commercial use and educational purposes.  
Please contact the team for contributions or questions.



