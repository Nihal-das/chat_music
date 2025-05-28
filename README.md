# ChatMusic 🎧💬

A Django-powered real-time chat app with synchronized music playback via Audius API.

## Features
- Real-time WebSocket chat
- Edit & delete messages
- Background music syncing
- User authentication
- Room-based chat with host controls

## Tech Stack
- Django + Channels
- JavaScript + WebSocket
- Audius Music API
- HTML/CSS + Bootstrap (or your flavor)

## Run Locally
```bash
git clone https://github.com/Nihal-das/chat_music.git
cd chat_muisc
python -m venv env
source env/bin/activate
pip install -r requirements.txt
python manage.py runserver
