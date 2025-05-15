
السلام عليكم

# 🗨️ Kothabarta (কথাবার্তা)
"কথাবার্তা" একটি সহজ, পরিচ্ছন্ন এবং রিয়েল-টাইম গ্রুপ চ্যাট অ্যাপ্লিকেশন, যা তৈরি করা হয়েছে Flask এবং Socket.IO ব্যবহার করে।

এই অ্যাপটি তৈরি করার মূল উদ্দেশ্য হলো — আমার প্রিয় বন্ধুমহলকে একটি ছোট কিন্তু অর্থবহ উপহার দেওয়া, যাতে তারা নিজেদের লোকাল এনভায়রনমেন্টে রান করে একসাথে রিয়েল-টাইমে কথোপকথনে অংশ নিতে পারে।

এই অ্যাপের মাধ্যমে একাধিক ব্যবহারকারী একইসাথে একটি চ্যাট রুমে যুক্ত হয়ে বার্তা আদান-প্রদান করতে পারবেন। এটি যেমন হালকা ও দ্রুতগতির, তেমনি ব্যবহারেও সহজ — বিশেষত শিক্ষার্থী ও বন্ধুদের মধ্যে ব্যবহারযোগ্য একটি বন্ধুবান্ধব পরিবেশ তৈরি করার লক্ষ্যেই এটি ডিজাইন করা হয়েছে।

# 🚀 Features
- 🔁 Real-time messaging using WebSockets
- 👥 Join public chat rooms
- 🆔 Unique username for each session
- 📦 Built with Flask and Socket.IO
- 🎨 Simple and clean UI (Tailwind-compatible)
- 🌐 Local or remote hosting support

# 🛠️ Technology 
  
 - Backend: Python, Flask, Flask-SocketIO
 - Frontend: HTML, CSS, JavaScript, used Tailwind Css also
 - Realtime Engine: WebSocket via SocketIO

## 📁 Project Structure

```bash
└── Kothabarta/
    ├── app/
    │   ├── controller/
    │   │   ├── user_controller.py
    │   │   └── chat_controller.py
    │   │  
    │   ├── routes/
    │   │   ├── default_route.py
    │   │   ├── user_route.py
    │   │   └── chat_route.py
    │   │  
    │   ├── templates/
    │   │   ├── index.html
    │   │   ├── chat.html
    │   │   └── base.html
    │   │  
    │   ├── static/
    │   │   ├── css/
    │   │   │   └── style.css
    │   │   └── js/
    │   │       └── chat.js
    │   │  
    │   └── __init__.py
    ├── .env
    ├── requirements.txt
    ├── Readme.md
    └── kothabarta.py
```

## 🔧 Installation & Setup

1. **Clone the repository**

```bash
	git clone https://github.com/lowercase-tousif/kothabarta.git
	cd kothabarta
```

2. **Create virtual environment & install dependencies**
```bash
	python -m venv venv
	source venv/bin/activate  # On Windows: venv\Scripts\activate
	pip install -r requirements.txt
```
3. **Run the application**
```bash
	on windows:
	python kothabarta.py

	on ubuntu or other distros:
	python3 kothabarta.py
```
4. **Visit the url**
```plaintext
	Then visit `http://127.0.0.1:5000` in your browser.
	your friend needs open the url too
```





