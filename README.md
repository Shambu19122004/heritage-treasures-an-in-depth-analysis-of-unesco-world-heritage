# heritage-treasures-an-in-depth-analysis-of-unesco-world-heritage


---

```markdown
# 🌍 Heritage Treasures: An In-depth Analysis of UNESCO World Heritage Sites

This project explores the global distribution, categorization, and risk status of UNESCO World Heritage Sites using interactive data visualizations and dashboards built in Tableau and integrated into a Flask web application.

## 🔗 Live Site

👉 [Visit the Project Website](https://heritage-treasures-an-in-depth-analysis-fyzx.onrender.com)

## 📽️ Video Explanation

🎬 *Coming Soon* – A walkthrough video explaining the project end-to-end.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Features](#features)
- [Data Source](#data-source)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Screenshots](#screenshots)
- [Acknowledgements](#acknowledgements)

---

## 🧭 Overview

This project presents a complete analytics pipeline:
- Data cleaning and preparation using the UNESCO World Heritage dataset.
- Multiple visualizations created in Tableau Public.
- Dashboards and storyboards covering heritage types, danger status, site age, and geographical trends.
- A Flask-powered interactive website that embeds all Tableau content seamlessly.

---

## 📁 Project Structure

```

heritage-treasures-an-in-depth-analysis/
│
├── Project Files/
│   ├── app.py                  # Flask backend
│   ├── templates/
│   │   └── index.html          # Main HTML page with embedded dashboards/stories
│   └── static/
│       ├── style.css           # CSS styles
│       └── images/             # Hero and landscape images
│
├── Documentation/
│   ├── Project\_Report.pdf      # Final documentation (as per templates)
│
├── Video/
│   └── TableauFlask.mp4        # Video explanation (to be added)
│
└── README.md                   # This file

````

---

## 📊 Features

✅ Cleaned dataset using key UNESCO heritage metadata  
✅ 8+ Tableau visualizations (pie charts, maps, bar graphs, forecasting, etc.)  
✅ 2 Tableau dashboards covering overall site analysis and endangered trends  
✅ 2 Tableau storyboards explaining key insights interactively  
✅ Responsive Flask web interface for viewing dashboards/stories  
✅ Deployed using Render.com

---

## 📂 Data Source

- **Dataset**: [UNESCO World Heritage Sites (Kaggle)](https://www.kaggle.com/datasets/ujwalkandi/unesco-world-heritage-sites)
- Columns include: `ID No.`, `Name`, `Country`, `Region`, `Category`, `Danger`, `Endangered Year`, `Date Inscribed`, etc.

---

## 🛠️ Technologies Used

| Component       | Technology                     |
|----------------|----------------------------------|
| Web Framework   | Flask (Python)                  |
| Data Visualization | Tableau Public              |
| Frontend        | HTML, CSS                       |
| Deployment      | Render.com                      |
| Version Control | Git & GitHub                    |

---

## 🚀 Setup Instructions (for local run)

1. Clone the repository:
   ```bash
   git clone https://github.com/Shambu19122004/heritage-treasures-an-in-depth-analysis-of-unesco-world-heritage.git
   cd heritage-treasures-an-in-depth-analysis-of-unesco-world-heritage
````

2. Create a virtual environment and install dependencies:

   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   pip install -r requirements.txt
   ```

3. Run the Flask app:

   ```bash
   python Project\ Files/app.py
   ```

4. Open your browser at: `http://127.0.0.1:5000`

> ⚠️ Note: Tableau Public dashboards may not display in local development due to CORS issues. Use the deployed link for full functionality.

---

## 🖼️ Screenshots

### 🌍 Dashboard 1 – Global Overview

![Dashboard1](https://public.tableau.com/static/images/da/dashboard1_17510154959140/Dashboard1/1.png)

### 📘 Story 2 – Timeline & Regional Trends

![Story2](https://public.tableau.com/static/images/UNESCO_Story1/Story2/1.png)

---

## 🙏 Acknowledgements

* **UNESCO** for making the dataset publicly available.
* **SmartInternz & APSCHE** for the guided project format.
* **Render.com** for free Flask app hosting.

---


