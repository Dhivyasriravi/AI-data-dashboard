# 📊 AI Data Dashboard

> Upload any CSV file — Claude AI auto-generates smart insights while Chart.js renders live interactive charts.

**Built by:** Dhivyasri Ravi | CSE Graduate 2026

---

## 🚀 Live Demo
[View Live](https://yourusername.github.io/ai-data-dashboard)

---

## 📌 About the Project
An intelligent data analytics dashboard where users upload any CSV file and instantly get AI-generated insights, interactive charts (bar, line, pie, donut), statistical summaries, and a data preview table — all in one page, no backend required.

---

## ✨ Features
- 📂 Drag & drop or click-to-upload any CSV file
- 🤖 Claude AI generates 5 specific data insights automatically
- 📊 4 chart types: Bar, Line, Pie, Donut (switchable live)
- 🔄 Dynamic X/Y axis column selector
- 📈 Auto-computed stats: rows, numeric columns, max, average
- 📋 Data preview table (first 10 rows)
- 🎯 Works with any CSV: sales, marks, weather, finance, HR data
- 💡 Sample dataset included for instant demo

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 / CSS3 / JavaScript | Frontend |
| Chart.js | Interactive data visualizations |
| PapaParse | CSV parsing |
| Claude API (Anthropic) | AI-generated data insights |

---

## ⚙️ How to Run

### Step 1 — Get API Key
```
1. Go to https://console.anthropic.com
2. Sign up (free) → API Keys → Create Key
3. Copy your key
```

### Step 2 — Add API Key to Code
```javascript
// Open ai_data_dashboard.html in VS Code
// Find this line and replace:
const API_KEY = 'YOUR_ANTHROPIC_API_KEY_HERE';
// Replace with:
const API_KEY = 'sk-ant-your-actual-key-here';
```

### Step 3 — Run
```bash
Option A: Double-click → open in Google Chrome
Option B: VS Code → Live Server → localhost:5500
Option C: Deploy on GitHub Pages (see below)
```

> ⚡ Note: Charts and stats work WITHOUT the API key. API key is only needed for AI Insights.

---

## 🌐 Deploy on GitHub Pages
```bash
1. Create GitHub repo: ai-data-dashboard
2. Upload file → rename to index.html
3. Settings → Pages → main branch → Save
4. Live at: https://yourusername.github.io/ai-data-dashboard
```

---

## 📁 Project Structure
```
ai-data-dashboard/
│
├── index.html        ← Complete project (single file)
└── README.md         ← Documentation
```

---

## 🧠 How It Works
1. User uploads CSV → PapaParse converts it to JSON
2. Stats are computed (min, max, avg, row count)
3. Chart.js renders charts based on selected columns
4. A compact dataset summary is sent to Claude API
5. Claude returns 5 specific insights which are displayed

---

## Sample Use Cases
-  Sales data analysis (monthly revenue, profit trends)
-  Student performance dashboard (marks, attendance)
-  Weather data visualization (temperature, rainfall)
-  Personal finance tracker (income vs expenses)
-  HR data insights (headcount, department stats)

---

## 🔮 Future Improvements
- [ ] Add export to PDF/PNG functionality
- [ ] Support Excel (.xlsx) file upload
- [ ] Add trend prediction using regression
- [ ] Multi-file comparison dashboard

---

## 👩‍💻 Author
**Dhivyasri Ravi**
-  dhivyasriravi5@gmail.com
-  [LinkedIn](https://linkedin.com/in/dhivyasri)
-  [GitHub](https://github.com/dhivyasri)

---

## 📄 License
MIT License — free to use and modify.

