# elderly-care-management-system
1 # Project Name
2 Elderly Care Management System
3
4 ## Description
5 Elderly Care Management System is a user-friendly application designed to help families manage and monitor the care of their elderly loved ones. With the increasing challenges of coordinating daily care, medication schedules, and ensuring safety, this system provides a centralized solution to streamline caregiving responsibilities.
6
7 ## Tech Stack
8 - Backend : Node.js / Express.js
9 - Frontend : React.js (web) & React Native (mobile)
10 - Database : PostgreSQL
12 - Other : Firebase Cloud Messaging (push notifications), Twilio (SMS reminders)
13
14 ## Features
15 - ✅ Personalized Care Plans – create, edit and assign daily routines and tasks per individual
16 - 💊 Medication Reminders – automated push & SMS alerts tied to prescribed schedules
17 - 🚨 Emergency Contact – one-tap alert system to notify designated family members or services
18 - 📋 Activity Logging – track meals, exercises, appointments and generate daily/weekly reports
19 - 🔐 User Authentication & Roles – secure login with Admin, Caregiver, and Family Member roles
20 - 📈 Analytics Dashboard – visualize adherence rates, missed reminders, and care plan effectiveness
21
22 ## Installation & Setup
23 1. Clone the repository:
24 bash 25 git clone https://github.com/your-org/elderly-care-management.git 26 cd elderly-care-management 27
28 2. Install backend dependencies and configure environment:
29 bash 30 cd backend 31 npm install 32 cp .env.example .env # configure DB_URL, JWT_SECRET, STRIPE_KEY, TWILIO_CRED 33 npm run migrate # run database migrations 34
35 3. Install frontend dependencies:
36 bash 37 cd ../frontend 38 npm install 39
40 4. Start development servers:
41 bash 42 # In one terminal: 43 cd backend && npm start 44 # In another terminal: 45 cd frontend && npm start 46
47
48 ## API Documentation
49 - Find the full Postman collection and environment files here:
50 Postman Collection →
51
52 ## Live Demo
53 - Web: https://elderly-care.app.demo.com
54 - Mobile (Expo): https://expo.dev/@your-username/elderly-care
55
56 ## Screenshots
57 1. Dashboard Overview
58

59 2. Care Plan Editor
60

61 3. Medication Reminder Popup
62

63
64 ## Contributing
65 1. Fork the repository
66 2. Create a feature branch (git checkout -b feature/your-feature)
67 3. Commit your changes (git commit -m "Add your feature")
68 4. Push to the branch (git push origin feature/your-feature)
69 5. Open a Pull Request and describe your changes in detail
70
71 ## License
72 This project is licensed under the MIT License. See the LICENSE file for details.
