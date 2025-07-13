
# 📚 Book Recommendation Chatbot (Watson AI)

A smart AI-powered virtual assistant built using **IBM Watson Assistant**, designed to recommend books based on user preferences like genre, mood, and age group.

---

✅ Recommends Books Based On:

- Genre (e.g., Mystery, Romance, Sci-Fi)
- Mood (e.g., Happy, Curious, Emotional)
- Age Group (e.g., Kids, Teen, Adult)

✅ Powered by IBM Watson:

- Built using Watson Assistant for intent recognition 🧠
- Interactive conversational flow with entities and dialogs
- Smart and personalized responses 💬

✅ User-Friendly UI:

- Clean and minimal chatbot interface 💻
- Quick reply buttons for faster input ⚡
- Real-time chat experience ⏱️

---

## 🖼️ Chatbot Preview

![Chatbot Screenshot](https://drive.google.com/uc?export=view&id=1X-DKN1_mrweFrIbiGCFnQtVy57_t799R)

---

## 💻 How to Run Locally

### 🔧 1. Clone the Repository

```bash
git clone https://github.com/Anuj-9628/Book_Recommendation_Sys.git
cd Book_Recommendation_Sys
```

---

### 🧰 2. Set Up IBM Watson Assistant

1. Go to [IBM Cloud](https://cloud.ibm.com/)
2. Create a **Watson Assistant** service
3. Import the provided skill JSON file (if available)
4. Save the following credentials:
   - `Assistant ID`
   - `API Key`
   - `Service URL`

---

### 📝 3. Add Your Credentials

Create a `.env` file in the root folder and add the following:

```env
WATSON_API_KEY=your-api-key
WATSON_URL=your-service-url
ASSISTANT_ID=your-assistant-id
```

Make sure your Python code reads from this `.env` file (use `python-dotenv` if needed).

---

### 📦 4. Install Python Dependencies

```bash
pip install -r requirements.txt
```

---

### 🚀 5. Run the Streamlit App

```bash
streamlit run app.py
```

---

## 📽 Output Examples

1. 📚 Book suggestions by genre  
2. 🤖 Interactive chat-based conversation  
3. 📊 Personalized recommendation messages  

---

## 🌐 Live Demo

🔗 _Coming Soon..._

---

## 🧑‍💻 Author

Developed by [Anuj](https://github.com/Anuj-9628)

---
