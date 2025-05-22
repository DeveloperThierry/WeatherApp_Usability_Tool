# 🌦️ Weather App Usability Testing Tool

My project is a **Streamlit-based usability testing tool** designed to receive user feedback and experience of my weather app interface. 

---

## 📋 Features

- Consent form to ethically record participant agreement  
- Demographic questionnaire (age, occupation, etc.)  
- Task simulation (timed, success tracking, notes)  
- Exit questionnaire (Likert scales and open-ended feedback)  
- Aggregated report view with interactive charts  

---

## 🛠️ How It Works

The app consists of six tabs:

1. **Home** – Introduction and overview  
2. **Consent** – Record participant consent  
3. **Demographics** – Collect user profile info  
4. **Task** – Observe and time user performance on tasks  
5. **Exit Questionnaire** – Capture satisfaction and feedback  
6. **Report** – View summarized results with visualizations  

---

## 📂 Folder Structure

```
weather-usability-tool/
├── data/
│   ├── consent_data.csv
│   ├── demographic_data.csv
│   ├── task_data.csv
│   └── exit_data.csv
├── usability_tool.py
└── README.md
```

---

## 📦 Requirements

- Python 3.7+  
- Streamlit  
- Pandas  

Install dependencies:

```bash
pip install streamlit pandas
```

---

## 🚀 Running the App

In the terminal, run:

```bash
streamlit run usability_tool.py
```

---

## 🧪 Sample Tasks Included

- Task 1: Find weather in your city  
- Task 2: View the neighboring city weather forecast  
- Task 3: Convert temperature between Fahrenheit and Celsius  

---

## 📈 Report Outputs

- Consent participation count  
- Average age of users  
- Familiarity distribution (bar chart)  
- Average task duration  
- Satisfaction & difficulty ratings (average + full table)  

---

## ✅ Data Privacy

- All data is stored anonymously in `.csv` files  
- Participants must give explicit consent before continuing  
- No sensitive or identifying information is required  

---

## ✍️ Author

**Thierry Laguerre**  

---

## 📄 License

This project is for **educational purposes** and is open for adaptation under the MIT License.
