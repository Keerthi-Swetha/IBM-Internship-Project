# 🔋 AURA — Smart Home Energy Advisor 

AURA (Automated Utility Resource Advisor) is an intelligent energy assistant that helps users monitor, analyze, and optimize electricity consumption. Built purely on software using IBM Cloud tools, AURA uses simulated usage data and machine learning to deliver real-time insights and personalized energy-saving tips without any physical hardware.

---

## 📌 Project Description

AURA acts like a virtual energy manager. It analyzes usage patterns, estimates bills, and suggests when and how to use appliances to save power and money. Users can interact with it using plain language queries such as:

- “Why is my electricity bill high?”
- “When should I run the washing machine?”
- “Did I meet my monthly energy target?”

Everything runs in the cloud with mock or imported data, making it easy to prototype and scale without needing smart meters.

---

## 🚀 Features

- **Usage Analysis**: View simulated or uploaded data to track daily, weekly, and monthly energy consumption.  
- **AI-Driven Tips**: Recommendations based on patterns like running heavy loads during off-peak hours.  
- **Custom Goals**: Set monthly usage targets and monitor progress.  
- **Alerts & Notifications**: Simulated warnings for unusual spikes or goal thresholds.  
- **Virtual Routines**: Simulate routines like “Night Mode” or “Away Mode” for better efficiency.  
- **Conversational Interface**: Ask energy-related questions through Watson Assistant for instant responses.

---

## 🧰 Tech Stack

| Layer               | Tools & Technologies                               |
|---------------------|----------------------------------------------------|
| Data & AI           | Python scripts, Pandas, scikit‑learn (Watson Studio notebooks) |
| Conversational Agent| IBM Watson Assistant                              |
| Backend Services    | Flask or Node.js (deployed via IBM Cloud Foundry or Code Engine) |
| Data Storage        | IBM Cloudant or Db2 on Cloud                      |
| Frontend Dashboard  | React.js or vanilla HTML/CSS/JS                   |

---

## 🗂️ Project Structure

```
aura-energy-advisor/
├── src/
│   ├── main.py         # Entry point and main loop
│   ├── advisor.py      # Core logic for suggestions
│   ├── data_handler.py # Loading and preprocessing input data
│   └── utils.py        # Helper functions
├── data/
│   └── sample_usage.json
├── docs/
│   └── flowchart.png
├── requirements.txt
└── README.md
```

---

## 🧑‍💻 Getting Started

1. **Clone the repo**  
   ```bash
   git clone https://github.com/Keerthi‑Swetha/IBM‑Internship‑Project.git
   cd aura-energy-advisor
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the agent**  
   ```bash
   python src/main.py
   ```

4. Optional: Set up Watson Assistant and the dashboard to enable full interaction and UI.

---

## 💬 Sample User Queries AURA Can Handle

- “How much energy did I use this week?”
- “Why is my bill high this month?”
- “Suggest ways to reduce my power consumption.”
- “What's the best time to run heavy appliances?”
- “Did I meet my energy goal this month?”

---

## 🔮 Future Scope

- Plug into real smart meters or IoT devices for real-time data.  
- Voice assistant integration (e.g., Alexa, Google Assistant).  
- Weather-aware scheduling and automation.  
- Gamification and energy challenges to boost engagement.  
- Insights at community or utility-provider level.

---

## 👥 End Users

- Homeowners and renters  
- Technology learners and students  
- Green living advocates  
- Utility customers  
- Educational institutions

---

## ⚖️ License

This project is licensed under the MIT License and intended for educational and demonstration use.

---

## 🙌 Contributions

Contributions, feature requests, and pull requests are welcome. Feel free to open issues for improvements or bug reports.

---

## 📄 Credits

Developed by Keerthi Swetha using IBM Cloud tools (Watson Studio, Watson Assistant, Cloudant, Cloud Foundry) as part of an IBM SkillsBuild internship project.

---
