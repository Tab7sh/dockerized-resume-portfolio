🌟 FULL-STACK DYNAMIC PORTFOLIO STACK 🌟
📌 PROJECT OVERVIEW 📌
Ye project aik mukammal End-to-End Microservice Architecture ko demonstrate karta hai. Is mein sirf aik static page nahi hai, balkay aik Python-Flask backend ko Redis database ke saath integrate kiya gaya hai taake live visitor analytics ko track aur save kiya ja sakay.

🛠 TECH STACK 🛠
🐍 Backend: Python 3.9 (Flask Framework)

⚡ Persistence Layer: Redis (High-speed In-memory Data Store)

🌐 Web Server: Nginx (Alpine-based for high performance)

🎼 Orchestration: Docker Compose

🐳 Containerization: Docker

🏗 ARCHITECTURE & IMPLEMENTATION 🏗
1️⃣ Containerized Services
💻 Frontend/App: Aik custom Docker image banayi gayi hai jo portfolio serve karti hai aur backend logic ko handle karti hai.

🗄️ Database: Aik Redis container deploy kiya gaya hai jo visitor counts ko permanently save rakhta hai.

2️⃣ Networking & Orchestration
🔗 Docker Compose: Iska use karte hue frontend aur backend ko aik private bridge network par jora gaya hai.

📡 Service Discovery: Is stack mein app Redis se uske service name (redis-db) ke zariye communicate karti hai, na ke kisi static IP se.

3️⃣ Data Persistence
💾 Volumes: Stack ko is tarah configure kiya gaya hai ke agar containers delete bhi ho jayen, tab bhi analytics data mehfooz rahega.

📊 PROJECT PROOF 📊
✅ Multi-Container Health Check
Dono Portfolio aur Redis containers synchronized aur active hain.

🌍 Live Application Access
Dynamic resume port 8080 par live hai aur real-time visitor tracking show kar raha hai.

🚀 QUICK START 🚀
📂 Clone the Repo:

Bash
git clone https://github.com/Tab7sh/Dynamic-DevOps-Portfolio.git
🏗 Launch the Stack:

PowerShell
docker-compose up -d --build
✨ Access App: Browser mein http://localhost:8080 kholen.

💡 KEY LEARNING OUTCOMES 💡
🎯 Multi-service container orchestration mein maharat hasil ki.

🔌 Real-time database connectivity ko containerized environment mein implement kiya.

⚙️ Port mapping aur internal Docker networking ko manage kiya.
