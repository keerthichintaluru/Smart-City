# 🌆 Sustainable Smart City Assistant

An AI-powered smart city assistant designed to promote sustainability, streamline city data analysis, detect anomalies, and enhance citizen engagement using cutting-edge technologies.

> This project was developed during my internship using technologies I explored and implemented hands-on.

---

## 🧠 Tech Stack

- **Frontend**: Streamlit  
- **Backend**: FastAPI  
- **LLM**: IBM Watsonx Granite  
- **Anomaly Detection**: Scikit-learn  
- **Vector Search**: Pinecone  
- **Embeddings**: Sentence Transformers  
- **Deployment**: Localhost

---

## 🚀 Features

- 🧠 **Policy Chat Assistant** – Ask questions about smart city sustainability using an LLM  
- 📤 **KPI Upload** – Upload city performance data via CSV (e.g., air quality, water usage)  
- ⚠️ **Anomaly Detection** – Automatically detect outliers in KPI values  
- 💬 **Citizen Feedback** – Submit and manage feedback from users  
- 🌱 **Eco Tips** – Generate AI-powered eco-friendly tips  
- 📊 **Summary Dashboard** – View interactive summaries and metrics

---

## 📁 Project Structure

```
├── backend/
│   ├── main.py
│   └── routers/
│       ├── chat.py
│       ├── feedback.py
│       ├── eco.py
│       ├── kpi.py
│       ├── anomaly.py
│       └── vector.py
│   └── models/, schemas/
├── frontend/
│   ├── smart_dashboard.py
│   └── components/
│       ├── summary_card.py
│       ├── feedback_form.py
│       └── ...
├── screenshots/
│   ├── dashboard_view.png
│   └── anomaly_example.png
├── README.md
```

---

## 🧪 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Shirisha-Kuruva/SustainableSmartCity.git
cd SustainableSmartCity
```

### 2. Start the Backend

```bash
cd backend
uvicorn main:app --reload
```

> Swagger Docs available at: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

### 3. Start the Frontend

```bash
cd frontend
streamlit run smart_dashboard.py
```

> Access Dashboard at: [http://localhost:8501](http://localhost:8501)
