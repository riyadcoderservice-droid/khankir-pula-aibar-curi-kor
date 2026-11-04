🚀 ASFFLIKEBD — FREE FIRE LIKE API

<p align="center">
  <img src="./logo.png" width="150" alt="ASFFLIKEBD Logo">
</p><h1 align="center">🔥 ASFFLIKEBD FREE FIRE LIKE API</h1><p align="center">
  <b>⚡ Ultra-Fast Async Like API Powered by Flask, AES Encryption & Protobuf</b>
</p><p align="center">
  <a href="https://t.me/AS_OWNER99">
    <img src="https://img.shields.io/badge/Telegram-@AS__OWNER99-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white">
  </a>
  <a href="https://asfflikebd.shop">
    <img src="https://img.shields.io/badge/Website-ASFFLIKEBD-000000?style=for-the-badge&logo=google-chrome&logoColor=white">
  </a>
</p><p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python">
  <img src="https://img.shields.io/badge/Framework-Flask-black?style=flat-square&logo=flask">
  <img src="https://img.shields.io/badge/Encryption-AES--CBC-green?style=flat-square">
  <img src="https://img.shields.io/badge/Protocol-Protobuf-orange?style=flat-square">
  <img src="https://img.shields.io/badge/Status-Active-success?style=flat-square">
</p>---

📖 About The Project

ASFFLIKEBD FREE FIRE LIKE API is a high-performance REST API project designed for Free Fire like operations using Python, Flask, AsyncIO, AES encryption, and Protobuf serialization.

The API is designed with an asynchronous request architecture, multi-region support, token management, and structured JSON responses.

It provides a simple endpoint for sending like requests and retrieving player information and like statistics.

Official Website: https://asfflikebd.shop

---

✨ Features

- ⚡ Ultra-Fast Async Request System
- 🔐 AES CBC Encryption
- 📦 Protobuf Serialization
- 🌍 Multi-Region Support
- 🧠 Smart Token Loader
- 🚀 Flask REST API
- 📊 Real Like Count Response
- 🔥 OB53 Supported
- 🛡 Full Error Handling
- ⚙️ VPS Optimized
- 🔄 Multi-Token Rotation
- 📡 JSON-Based API Response
- 🧩 Modular Project Structure
- 🚀 High-Speed Request Processing

---

🌍 Supported Regions

Region| Code
Bangladesh| BD
India| IND
Brazil| BR
United States| US
North America| NA
SAC| SAC

---

📂 Project Structure

project/
│
├── app.py
│
├── like_pb2.py
├── like_count_pb2.py
├── uid_generator_pb2.py
│
├── token_bd.json
├── token_br.json
├── token_ind.json
│
├── requirements.txt
│
└── README.md

---

📦 Requirements

Install Packages

Install all required Python dependencies using:

pip install -r requirements.txt

requirements.txt

flask
aiohttp
requests
pycryptodome
protobuf

---

🔑 Token Configuration

The API uses region-specific JSON token files to manage authentication tokens.

📁 token_bd.json

[
  {
    "token": "YOUR_JWT_TOKEN"
  },
  {
    "token": "YOUR_JWT_TOKEN_2"
  }
]

📁 token_br.json

[
  {
    "token": "YOUR_JWT_TOKEN"
  }
]

📁 token_ind.json

[
  {
    "token": "YOUR_JWT_TOKEN"
  }
]

Important: Replace the placeholder values with valid tokens. Keep your authentication tokens private and never publish real tokens in a public repository.

---

▶️ Run The Server

Start the Flask API server using:

python app.py

Local Server Address

http://127.0.0.1:5000

---

⚙️ Production Deployment

The API can be deployed on a VPS or Linux-based server using different process managers.

🚀 Gunicorn

gunicorn -w 4 -k gthread -b 0.0.0.0:5000 app:app

🔥 PM2

pm2 start app.py --interpreter python3 --name ff-like-api

🛠 Supervisor

Create a Supervisor configuration file:

sudo nano /etc/supervisor/conf.d/fflike.conf

Supervisor Configuration

[program:fflike]
directory=/root/project
command=python3 app.py
autostart=true
autorestart=true
stderr_logfile=/var/log/fflike.err.log
stdout_logfile=/var/log/fflike.out.log

Restart Supervisor

sudo supervisorctl reread
sudo supervisorctl update
sudo supervisorctl restart fflike

---

📌 API Documentation

Endpoint

GET /like?uid={uid}&server_name={region}

Parameters

Parameter| Type| Description
uid| Integer| Free Fire Player UID
server_name| String| Player's server region

---

✅ Example Request

https://your-domain.com/like?uid=123456789&server_name=BD

Example Response

{
  "LikesGivenByAPI": 220,
  "LikesafterCommand": 2034,
  "LikesbeforeCommand": 1880,
  "PlayerNickname": "ARYAN SHANTO",
  "UID": 123456789,
  "status": 1
}

---

📊 Response Explanation

Key| Description
LikesGivenByAPI| Total Likes Added
LikesafterCommand| Likes After Request
LikesbeforeCommand| Likes Before Request
PlayerNickname| Player Name
UID| Free Fire Player UID
status| 1 = Success
status| 2 = Failed

Status Codes

- "1" — Request Successful
- "2" — Request Failed

---

🔥 Performance & Optimization

- ⚡ 250 Async Requests Per Command
- 🔄 Multi-Token Rotation
- 💾 Low RAM Usage
- 🚀 High-Speed Response Processing
- ⚙️ VPS Optimized
- 📡 Fast Like Delivery
- 🧠 Efficient Token Management
- 🔐 Encrypted Request Processing

---

🛠 Built With

Technology| Purpose
Python| Core Programming Language
Flask| REST API Framework
AsyncIO| Asynchronous Processing
AioHTTP| Async HTTP Requests
Requests| HTTP Communication
PyCryptodome| AES Encryption
Protobuf| Binary Serialization

---

🧠 Encryption & Authentication

This API uses multiple technologies for request processing and authentication.

Encryption Technologies

- 🔐 AES CBC Encryption
- 📦 Protobuf Encoded Binary Requests
- 🔑 Bearer Token Authentication
- 🛡 Structured Authentication Handling

These components are used to process API requests and communicate with supported services.

---

👨‍💻 Developer Information

<p align="center">
  <b>DEVELOPED & MAINTAINED BY</b>
</p><h2 align="center">🔥 ARYAN SHANTO</h2><p align="center">
  <a href="https://t.me/AS_OWNER99">
    <img src="https://img.shields.io/badge/Telegram-@AS__OWNER99-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white">
  </a>
</p><p align="center">
  <a href="https://asfflikebd.shop">
    <img src="https://img.shields.io/badge/Official%20Website-ASFFLIKEBD-000000?style=for-the-badge&logo=google-chrome&logoColor=white">
  </a>
</p>---

🌐 Official Website

<p align="center">
  <a href="https://asfflikebd.shop">
    <img src="https://img.shields.io/badge/VISIT-ASFFLIKEBD.SHOP-blue?style=for-the-badge&logo=google-chrome&logoColor=white">
  </a>
</p>Website: https://asfflikebd.shop

---

⚠️ Disclaimer

This project is developed and shared for educational and informational purposes only.

- The developer is not responsible for unauthorized or improper use.
- Users are responsible for complying with applicable game rules, service terms, and laws.
- This project is not affiliated with, endorsed by, or officially associated with Garena or Free Fire.
- Use this project at your own risk.

---

⭐ Support The Project

If you find this project useful, you can support its development:

⭐ Star This Repository
🍴 Fork This Repository
📢 Share With Friends

Your support and feedback are always appreciated!

---

❤️ Thanks For Using ASFFLIKEBD

<p align="center">
  <b>MADE WITH ❤️ BY ARYAN SHANTO</b>
</p><p align="center">
  <b>ASFFLIKEBD — FAST • RELIABLE • PROFESSIONAL</b>
</p><p align="center">
  🌐 https://asfflikebd.shop
</p>