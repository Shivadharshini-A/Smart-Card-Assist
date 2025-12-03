 🩺 MediAssist – RFID Smart Patient Dashboard

MediAssist is an IoT-based hospital system that uses **RFID + NodeMCU + Web Dashboard + Gemini AI** to instantly retrieve and manage patient medical records.

🚀 How It Works
1. Patient taps RFID card on the **NodeMCU (ESP8266) + RC522 reader**
2. The UID is sent to backend through Wi-Fi.
3. The dashboard loads:
   - Patient identity
   - Medical history
   - Current condition
   - Diet plan
   - Case studies
   - Doctor notes
   - AI chatbot for medical guidance

✨ Key Features
✔ RFID-based instant patient lookup  
✔ Lifetime medical history storage  
✔ Disease-specific diet plan + **Download as PDF**  
✔ Doctor notes & visit logs  
✔ **AI Chatbot (Gemini API)** for first aid, monitoring & guidance  
✔ Case studies showing how similar cases were handled  
✔ Auto-updating dashboard (no refresh needed)

🧱 Tech Stack
Layer | Technology 
Hardware | NodeMCU ESP8266, RFID RC522, LED + Buzzer 
Firmware | Arduino (C++) 
Backend | Node.js + Express 
AI | Google Gemini (generative AI API) 
Frontend | HTML, Bootstrap, JavaScript 

📂 Important Files
File | Purpose 
nodemcu.ino | Handles RFID scanning & Wi-Fi communication 
server.js | Backend server + chatbot + PDF generation 
dashboard.html| Smart UI showing patient data & controls 


