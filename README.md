# ⚖️ BMI Calculator Web & CLI App

This project includes both a **web-based BMI Calculator** built with Flask and a **command-line version** using Python. It allows users to calculate their **Body Mass Index (BMI)** based on height and weight and displays the BMI category (Underweight, Normal, Overweight, Obese).

---

## 🌐 Web Version (Flask)

### 🔍 Features
- Input: Name, Height (m), Weight (kg)
- Real-time BMI calculation and category display
- Saves results with timestamps to a file (`bmi_data.txt`)
- Displays BMI history (last 10 entries)
- Option to delete the most recent entry
- Flash messages for validation and success alerts

### 🛠️ Tech Stack
- Python  
- Flask  
- HTML + Jinja  
- File handling (no database needed)

### 📁 Folder Structure
<img width="490" height="325" alt="image" src="https://github.com/user-attachments/assets/ac2388a2-7a47-4015-9523-cc316e775bac" />

### 📸 Screenshots:
index.html= <img width="1319" height="613" alt="image" src="https://github.com/user-attachments/assets/585ed798-b1e4-477b-822f-068676f6f84d" />
result.html= <img width="852" height="524" alt="image" src="https://github.com/user-attachments/assets/919fdebe-c283-4230-b5a5-ab9b5efb7ce9" />
history.html= <img width="922" height="499" alt="image" src="https://github.com/user-attachments/assets/45bc7562-e71c-4dc5-9373-d31f0ad1e66f" />




### How to Run:
 Run the app:
python bmi_cal.py

Open in browser:
http://127.0.0.1:5000

### 📝 BMI Categories:

Underweight: BMI < 18.5
Normal: 18.5 ≤ BMI < 25
Overweight: 25 ≤ BMI < 30
Obese: BMI ≥ 30

### 👩‍💻 Created By:
Pari Sharma
🎓 BCA Student | Data Science & Web Dev Enthusiast


### 📄 License
Open-source project for educational purposes.

