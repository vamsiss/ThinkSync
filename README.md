# ThinkSync

**ThinkSync** is a full-stack real-time collaboration platform built using Django. It allows users to create rooms, chat, rate sessions, and interact in real-time. The project is now being extended into a Chrome Extension to support synchronized video watching.

## 🌟 Features

- User registration and authentication  
- Topic-based room creation  
- Real-time chat within rooms  
- Participant tracking  
- Room rating system  
- Dynamic topic generation via `get_or_create`  
- Responsive UI with Django templates  
- Planned browser extension integration for video sync  

## 🧠 Tech Stack

- **Backend**: Django, Django ORM  
- **Frontend**: HTML, CSS, Django Templates  
- **Database**: SQLite (development), supports PostgreSQL  
- **Real-Time**: Django Channels / Socket.IO (planned)  
- **Extension**: Manifest V3 Chrome Extension (in development)  

# Clone the repo
- git clone https://github.com/vamsiss/ThinkSync.git
- cd ThinkSync/ThinkSync

# Set up virtual environment
- python -m venv venv
- source venv/bin/activate  # or venv\\Scripts\\activate on Windows

# Run migrations
- python manage.py migrate

# Start the server
- python manage.py runserver

## 📂 Project Structure
- base/: Main Django app

- templates/: Frontend views

- static/ : CSS and JS assets

- ThinkSync/ : Project configuration files

🙌 Author
Sai Surya Tumpati
Built with a passion for real-time systems and virtual collaboration.
