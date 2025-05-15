
# السلام عليكم
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
   

## Data Flow Diagram ( Beginner Don't know if it's okay or not)

![kothabarta_dfd](https://media-hosting.imagekit.io/852494cdbe1a47fd/Screenshot%20from%202025-05-15%2018-28-34.png?Expires=1841920131&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=ONX5QRvSDYU3x90KUXal1nCFsK1sLn4nJjPi4-TRMd6C1PCpUwMDRl5c2OVY5As1OGKcFF1PYt7yFGFe8d29MFnDjEKrMl-Cs2X3NSxX3f28gnYqJacbL6ML5GpKHOU0GvjzgC7AalF8tUt6b3t8STJnV2k0-oZ8brtBRb~aZmQo368Ur4hQXm6nlcJ690SoSSUzrpFqV9YVE2zRvby3xQYLSBB32IDaqZyKyG1gdW2yNVGiu76eCLOaz-M0E8zevzQ5IxUHnWMaHg7aDIENHqhFEOS~VuRLlbUvvMauaBMPZ6Wh0E3YsoJXVRWfOb6pdVRvjyOv~Aw1aEPdFNwAUg__)


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




