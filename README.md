# smart-voting-system
🗳️ Smart Voting System
A secure, user-friendly Smart Voting System that allows voters to cast their votes electronically while ensuring transparency, authentication, and real-time result processing. Built using Python, Flask (or Django), and database support.

🎯 Objective
To design and develop a digital voting platform that:

Prevents fraud

Authenticates voters securely

Allows fair and fast voting

Provides real-time result tallying

🛠️ Features
✅ Voter Registration
✅ Admin Login Panel
✅ Voter Login with OTP or password
✅ Candidate Management
✅ Cast Vote (only once per voter)
✅ Live Result View
✅ Voting Period Control
✅ Blockchain-based (optional advanced security)

👨‍💻 Technologies Used
Frontend: HTML, CSS, JavaScript (Bootstrap)

Backend: Python (Flask or Django)

Database: SQLite / MySQL / Firebase

Optional: Blockchain (for tamper-proof logging), Face Recognition

🔐 Authentication
Each voter has a unique ID and credentials

OTP or biometric/face ID (optional)

Admin approves registered voters

🗂️ Project Structure
csharp
Copy
Edit
smart-voting-system/
├── app.py                 # Flask backend
├── templates/             # HTML templates
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   └── results.html
├── static/                # CSS, JS
├── database.db            # SQLite DB file
├── README.md
└── requirements.txt
🧪 How to Run
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/smart-voting-system.git
cd smart-voting-system
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the App
bash
Copy
Edit
python app.py
App will run at http://127.0.0.1:5000
