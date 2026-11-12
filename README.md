
# ✈️ Airline Dashboard

An interactive dashboard built with **Python, Pandas, Plotly Express, and Dash** that shows the proportion of flights by distance group (250-mile intervals).

<img width="1240" height="602" alt="Airline_dashboard" src="https://github.com/user-attachments/assets/2e0cc7d8-7e96-4eb2-a465-a4764b1dfde8" />


## 📌 Overview

This project loads a real-world airline dataset, samples 1,000 random records, and visualizes how flights are distributed across distance groups in an interactive pie chart served through a Dash web app.

## 🛠️ Tech Stack

- **Python 3**
- **Pandas**: data loading and sampling
- **Plotly Express**: chart creation
- **Dash**: web application framework

## 📂 Project Structure

```
├── airline_dashboard.py   # Main application
├── requirements.txt       # Dependencies
├── screenshot.png         # Dashboard preview
└── README.md
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

### 2. (Optional) Create a virtual environment

```bash
python -m venv venv
venv\Scripts\activate        # Windows
source venv/bin/activate     # macOS/Linux
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Run the app

```bash
python airline_dashboard.py
```

### 5. Open the dashboard

Go to **http://127.0.0.1:8050** in your browser.

> The app runs locally on your machine. The data is downloaded from the internet on startup, so you need an active connection.

## 📊 Features

- Loads the airline dataset directly from a remote CSV
- Reproducible sampling (`random_state=42`)
- Interactive pie chart with hover details
- Styled dashboard title and description

## 🧠 What I Learned

- Reading and sampling datasets with Pandas
- Building interactive charts with Plotly Express
- Structuring a web app layout with Dash components
- Debugging common issues (case-sensitive column names, syntax errors, interpreter mismatches)

## 🔮 Future Improvements

- Add dropdown filters (year, airline, airport)
- Add more charts (bar, line, map)
- Make the dashboard callbacks interactive
- Deploy the app online

## 📄 Data Source
https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/airline_data.csv
Airline dataset provided through the IBM Developer Skills Network data visualization course.

## 👤 Author

**Mohamed**
[LinkedIn](https://www.linkedin.com/in/your-profile) · [GitHub](https://github.com/your-username)
