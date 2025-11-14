# 🛒 Mini E-commerce Website (Flask)

A lightweight mini e-commerce web application built with the Flask Web Framework, featuring multiple pages, a master layout template, a contact form, and Telegram Bot API integration for real-time notifications.

## 🚀 Live Demo
**Render Deployment:**  
https://mini-ecommerce-3-cc88.onrender.com

## 📦 GitHub Repository
https://github.com/jackanyson271221-hub/mini-ecommerce/

## 🎥 Video Demonstration
https://youtu.be/tF2jbmd3KZ0

## 📌 Features

### 🌐 Pages Included
- **Home Page** – Main landing page
- **Cart Page** – Simple cart layout
- **About Page** – Store information
- **Contact Page** – Sends messages directly to Telegram
- **Layout Template** – A master page shared across all templates

### 🔧 Core Flask Features
- GET & POST routing
- HTTP request handling
- Jinja2 template inheritance
- Static file handling
- Form submission and validation
- Telegram Bot API integration
- Deployment on Render

## 🧰 Tech Stack

### Backend
- Python 3.x
- Flask Framework

### Deployment
- Render Cloud Application Platform

## 📁 Project Structure
```
│── static/
│   ├── css/
│   ├── images/
│
│── templates/
│   ├── layout.html
│   ├── index.html
│   ├── about.html
│   ├── cart.html
│   ├── contact.html
│
│── app.py
│── requirements.txt
│── README.md
```

## 🔨 Installation & Setup

### 1. Clone Repository
```bash
git clone https://github.com/jackanyson271221-hub/mini-ecommerce.git
cd mini-ecommerce
```

### 2. Create Virtual Environment (optional)
```bash
python -m venv venv
source venv/bin/activate   # MacOS/Linux
venv\Scripts\activate      # Windows
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure Telegram Bot
Create environment variables:
```
TELEGRAM_BOT_TOKEN=your_bot_token
TELEGRAM_CHAT_ID=your_chat_id
```

### 5. Run Application
```bash
python app.py
```
App will run at:
```
http://127.0.0.1:5000/
```

## 📨 Contact Form (Telegram Integration)
The Contact Page sends user messages directly to Telegram using your bot token and chat ID.

## 📚 Usage
- Open the homepage
- Navigate through About, Cart, and Contact pages
- Submit the Contact Form → Receive message on Telegram
- Customize layout via layout.html
- Modify static assets in static/

## 🛠 Requirements
```
Flask
requests
gunicorn
```

## 🔮 Future Improvements
- Add product listings
- Implement cart sessions
- Add admin dashboard
- Integrate database
- Add payment integration

## 👥 Contributors
**Jack Anyson** – Developer & Maintainer

## 📄 License
Open-source (choose your license; MIT recommended)
