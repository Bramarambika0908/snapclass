# 📚 SnapClass — AI-Powered Attendance System

SnapClass is an AI-powered attendance management system that automates student attendance using **Face Recognition and Voice Recognition**.
-> It provides separate interfaces for teachers and students, allowing teachers to manage subjects and students while students can mark attendance through an AI-based face scan.

## 🚀 Features:
- Teacher & student registration and login
- Secure password hashing using `bcrypt`
- Create and manage subjects
- Enroll students into subjects
- Face-based & Voice-based  Automatic attendance detection
- View enrolled & attendance history
- 🗄️ Cloud Database | Stores application data using Supabase
- can also perform **grouped face & voice Recognition**

##🛠️Requirements: 

*Python 3.7+ (mostly prefer 3.11)
*Webcam
*Required Python packages (listed in requirements.txt)

## Installation
1. Clone this repository
2. Install the required packages:
[**pip install -r requirements.txt**]

## 🔐 Supabase Configuration
configure Streamlit Secrets:
Manage app
→ Settings
→ Secrets
* SUPABASE_URL
* SUPABASE_KEY
## Usage
Run the application:
** streamlit run app.py**

### ☁️ Deployment
[snapclass link:](https://snapclass-03.streamlit.app/)
