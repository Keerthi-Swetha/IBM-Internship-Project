# IBM-Internship-Project
# 🌟 AURA – Smart Home Energy Advisor (Software-Only)

**AURA (Automated Utility Resource Advisor)** is a smart, software-based energy assistant that helps users monitor, analyze, and optimize their home’s energy consumption — intelligently and effortlessly.  
This project focuses purely on software functionalities without requiring any physical hardware or device integration.

---

## 🔧 Features

- 📊 **Energy Usage Tracking**  
  Analyze daily, weekly, and monthly energy usage from simulated or user-provided data.

- 💡 **Smart Recommendations**  
  Get personalized energy-saving tips based on usage patterns and goals.

- 🎯 **Goal Setting**  
  Set custom energy usage targets and track your progress over time.

- 🔔 **Notifications & Alerts**  
  Receive simulated alerts for unusual usage spikes or when nearing usage limits.

- 🧠 **Virtual Routines**  
  Create energy-efficient routines like “Night Mode” or “Away Mode” for better power management (simulated).

---

## 📁 Project Structure

aura-energy-advisor/
│
├── src/ # Core logic and processing
│ ├── main.py # Entry point / agent loop
│ ├── advisor.py # AURA's reasoning and suggestions
│ ├── data_handler.py # Input/output and mock data utilities
│ └── utils.py # Helper functions
│
├── data/ # Sample usage data
│ └── sample_usage.json
│
├── docs/ # Documentation and diagrams
│ └── flowchart.png
│
├── requirements.txt # Python dependencies
├── LICENSE
└── README.md # This file


---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Keerthi-Swetha/aura-energy-advisor.git
cd aura-energy-advisor

### 2. Install dependencies
pip install -r requirements.txt

### 3. Run the agent
python src/main.py


💬 Example Queries AURA Can Answer
“How much energy did I use this week?”

“Suggest a way to lower my electricity bill.”

“Did I meet my energy goal this month?”

“Create a virtual night mode.”

“What’s the best time to run my devices?”

🔐 Limitations
Software-only: AURA does not control physical devices.

Uses mock or user-provided data for simulation.

Works best with accurate input for meaningful insights.

📄 License
This project is licensed under the MIT License.

🤝 Contributing
Pull requests are welcome! Feel free to open issues for bugs, feature requests, or enhancements.


