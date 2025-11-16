📌 Project Overview

The Employee Performance Tracker helps organizations maintain structured data about employee performance.
It supports adding employees, tracking their performance metrics, updating records, generating reports, and exporting data for further analysis.

🚀 Features

➕ Add New Employees

📝 Record and Update Performance Metrics

📊 Calculate Performance Score

📅 Track Monthly or Weekly Performance

📁 Store Data in CSV / JSON

📈 Generate Reports (Text/CSV)

🔍 Search Employee Records

🗑️ Delete Employee Data

🧮 Simple and clear calculations

🛠️ Technologies Used

Python 3.x

Pandas (optional for advanced data handling)

JSON / CSV for storage

Matplotlib (optional for visual reports)

📂 Project Structure
employee-performance-tracker/
│
├── data/
│   ├── employees.json
│   └── performance.csv
│
├── src/
│   ├── main.py
│   ├── employee.py
│   ├── performance_manager.py
│   └── report_generator.py
│
├── README.md
└── requirements.txt

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/yourusername/employee-performance-tracker.git
cd employee-performance-tracker

2️⃣ Create Virtual Environment
python -m venv venv
source venv/bin/activate        # Linux/Mac
venv\Scripts\activate           # Windows

3️⃣ Install Dependencies
pip install -r requirements.txt

▶️ Usage
Run the main program
python src/main.py
