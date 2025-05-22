## 📺 Video Demonstration

Watch the full 3-minute demo video on YouTube here:  
🎥 **[https://youtu.be/tZI-_8gQ0hA](https://youtu.be/tZI-_8gQ0hA)**

[![Watch the demo video](https://img.youtube.com/vi/tZI-_8gQ0hA/0.jpg)](https://youtu.be/tZI-_8gQ0hA)


# 🛠️ Setup Instructions – WeatherApp_Usability_Tool

This guide will help you set up and run the **Streamlit-based usability testing tool** for evaluating a weather app interface.

---

## 📦 Prerequisites

Make sure you have the following installed on your system:

- Python 3.7 or higher  
- `pip` (Python package installer)  

---

## 🔧 Installation Steps

1. **Clone the Repository**

```bash
git clone https://github.com/developerthierry/WeatherApp_Usability_Tool.git
cd WeatherApp_Usability_Tool
```

2. **(Optional) Create a Virtual Environment**

```bash
python -m venv venv
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
```

3. **Install Required Packages**

```bash
pip install -r requirements.txt
```

> If you don't have a `requirements.txt`, install the packages manually:

```bash
pip install streamlit pandas
```

---

## 📂 Project Structure

```
WeatherApp_Usability_Tool/
├── data/                        # CSV data storage
│   ├── consent_data.csv
│   ├── demographic_data.csv
│   ├── task_data.csv
│   └── exit_data.csv
├── usability_tool.py            # Main Streamlit app
└── README.md                    # This file
```

> ℹ️ The `data/` folder is created automatically when the app runs.

---

## 🚀 Running the App

Launch the app from the terminal:

```bash
streamlit run usability_tool.py
```

This opens a browser tab running the usability testing interface.

---

## 🧪 Using the App

1. Start on the **Home** tab.
2. Navigate through:
   - **Consent**
   - **Demographics**
   - **Task**
   - **Exit Questionnaire**
   - **Report**
3. Each submission is saved into the corresponding CSV in the `data/` directory.

---

## ✅ Notes

- Mock/test data can be pre-filled into the CSV files for demo purposes.
- Reports include:
  - Consent count
  - Average age
  - Task success and time
  - Satisfaction and difficulty ratings

---

## 🔗 Repository

[GitHub Repo: developerthierry/WeatherApp_Usability_Tool](https://github.com/developerthierry/WeatherApp_Usability_Tool)

---

## 📄 License

This project is provided for educational use under the MIT License.

---

## 🙋 Author

**Thierry**  
GitHub: [@developerthierry](https://github.com/developerthierry)
