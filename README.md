   # Fake-Profile-Detection-System
🔍 FakeGuard - Complete System Overview
Files Created
Table
File	Description
app.py	Main Flask application with full detection engine
requirements.txt	Python dependencies
README.md	Complete GitHub repository description s

LICENSE	MIT License
PROJECT_SUMMARY.txt	Detailed project documentation
Templates (8 HTML files in /templates/)
Table
Template	Purpose
base.html	Master layout with navbar, particles animation, dark theme
index.html	Homepage with hero section, stats, features, recent analyses
analyze.html	Single profile analysis form with loading animation
result.html	Analysis results with risk gauge, radar chart, red/green flags
dashboard.html	User dashboard with stats cards, doughnut chart, history table
login.html	Secure login page
register.html	User registration page
about.html	Project info, tech stack, mission
batch_analyze.html	Batch JSON analysis page
✨ Key Features
🧠 Multi-Factor Detection Engine
Username Analysis — Detects bot patterns, random strings, impersonation
Profile Picture Scan — Identifies missing photos, stock images, AI-generated pics
Bio Analysis — Scans for spam keywords, scams, suspicious links
Activity Patterns — Analyzes follower ratios, posting frequency, account age
Network Mapping — Detects bot networks and connection anomalies
AI Risk Scoring — Weighted multi-factor calculation (0-100 scale)
🎨 Stunning UI/UX
Dark gradient theme with purple/blue accents
Floating particle background animation
Glass-morphism card effects
Animated SVG risk gauge
Interactive Chart.js radar & doughnut charts
Smooth fade-in animations
Fully responsive (mobile + desktop)
🔐 Security & Auth
Password hashing with Werkzeug
Flask-Login session management
SQL injection prevention (SQLAlchemy)
XSS protection (Jinja2 auto-escaping)
📡 API & Batch Support
REST API endpoint: POST /api/analyze
Batch analysis via JSON input
Analysis history tracking
System-wide statistics
🚀 How to Run
bash
Copy
# 1. Install dependencies
pip install -r requirements.txt

# 2. Run the application
python app.py

# 3. Open browser
http://localhost:5000

# Default login: admin / admin123
📊 Risk Scoring
Table
Score	Level	Verdict
0-24	Low	✅ Genuine
25-49	Medium	⚠️ Suspicious
50-74	High	⚠️ Suspicious
75-100	Critical	🚨 Fake

FakeGuard is an advanced AI-powered fake profile detection system built with Python and Flask. It uses a multi-factor analysis engine to identify fraudulent social media accounts by analyzing username patterns, profile pictures, bio content, activity metrics, and network relationships. Features include single & batch profile analysis, interactive risk visualization with Chart.js, user authentication, REST API, and a stunning dark-themed responsive UI. Perfect for cybersecurity researchers, social media platforms, and digital investigators.

contact for more (professorshami435@gmail.coms)
